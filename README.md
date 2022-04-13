# memariad
[github memariad](https://github.com/mermaid-js/mermaid)
[mermaid-js website](http://mermaid-js.github.io/mermaid/#/)
[article on github memariad](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)

```mermaid
	erDiagram
    CUSTOMER }|..|{ DELIVERY-ADDRESS : has
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER ||--o{ INVOICE : "liable for"
    DELIVERY-ADDRESS ||--o{ ORDER : receives
    INVOICE ||--|{ ORDER : covers
    ORDER ||--|{ ORDER-ITEM : includes
    PRODUCT-CATEGORY ||--|{ PRODUCT : contains
    PRODUCT ||--o{ ORDER-ITEM : "ordered in"

```
