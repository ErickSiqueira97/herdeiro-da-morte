# Mangá

Produção da adaptação em mangá de *O Herdeiro da Morte*. Esta pasta guarda capas, páginas e a licença dos modelos usados na arte. O manuscrito e o cânone continuam nas notas do vault; nada aqui promove status canônico.

## Fluxo

1. A arte é gerada fora do vault e entra só quando a versão da página está escolhida.
2. Capas ficam em `capas/volN/`, uma pasta por volume.
3. Cada capítulo fica em `capitulo-NN/`, com as imagens em `paginas/` e a ordem de leitura no `README.md` do capítulo.
4. Preto e branco e cor são variantes da mesma página (`*_bw` e `*_color`). A lista de páginas conta uma entrada por página, não por variante.
5. O `README.md` do capítulo registra ordem, beat e o que ainda falta (balões, ligação com o manuscrito). Enquanto esses campos estiverem vazios, a lista é placeholder.

## Estrutura

```
manga/
├── README.md
├── LICENSE-ARTE.md
├── capas/
│   └── vol1/
│       ├── capa_vol1_v2_titulo.jpg
│       ├── capa_vol1_v2_sem_texto.jpg
│       └── capa_vol1_v2_pb.jpg
└── capitulo-01/
    ├── README.md
    └── paginas/
        ├── revelacao_p1_bw.jpg
        ├── revelacao_p1_color.jpg
        ├── revelacao_p2_bw.jpg
        ├── revelacao_p2_color.jpg
        ├── revelacao_p3_bw.jpg
        └── revelacao_p3_color.jpg
```

| Caminho | Conteúdo |
|---|---|
| `capas/vol1/capa_vol1_v2_titulo.jpg` | Capa do volume 1 com título |
| `capas/vol1/capa_vol1_v2_sem_texto.jpg` | Mesma capa, sem lettering |
| `capas/vol1/capa_vol1_v2_pb.jpg` | Mesma capa, preto e branco |
| `capitulo-01/paginas/` | Três páginas de revelação, cada uma em pb e cor |
| `capitulo-01/README.md` | Lista de páginas (placeholder) |
| `LICENSE-ARTE.md` | Cópia e links da licença dos modelos |

## Licença da arte

As imagens foram geradas com Animagine XL 4.0 e inpainting de SDXL, sob a licença CreativeML Open RAIL++-M. A cópia integral e os links oficiais estão em [LICENSE-ARTE.md](LICENSE-ARTE.md).
