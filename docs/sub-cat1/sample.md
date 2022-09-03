# MkDocs Sample

## Admonitions

!!! Info
    Infomation

!!! Warning
    Warning info

??? Info
    Can be folded

## Font Awesome

:fa-external-link: [MkDocs](http://www.mkdocs.org/)  

## Codehilite

``` C
#include studio.h
void main(){
    printf("hello¥n");
}
```

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Diagram

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

## Tables

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |
