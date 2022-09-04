# MkDocs Sample

## Admonitions & Details

!!! Info
    Infomation

!!! Warning
    Warning info

??? Info
    Can be folded

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.

## Font Awesome

:fa-external-link: [MkDocs](http://www.mkdocs.org/){:target="_blank"}.  

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

=== "Output"
    | Method      | Description                          |
    | ----------- | ------------------------------------ |
    | `GET`       | :material-check:     Fetch resource  |
    | `PUT`       | :material-check-all: Update resource |
    | `DELETE`    | :material-close:     Delete resource |
=== "Markdown"
    ```
    | Method      | Description                          |
    | ----------- | ------------------------------------ |
    | `GET`       | :material-check:     Fetch resource  |
    | `PUT`       | :material-check-all: Update resource |
    | `DELETE`    | :material-close:     Delete resource |
    ```


## Keys
Reference is :fa-external-link: [here](https://facelessuser.github.io/pymdown-extensions/extensions/keys/){:target="_blank"}.  

=== "Output"
    ++ctrl+alt+delete++
=== "Markdown"
    ```
    ++ctrl+alt+delete++
    ```

## Tabs
=== "Output"

    === "Tab 1"
        Markdown **content**.

        Multiple paragraphs.

    === "Tab 2"
        More Markdown **content**.

        - list item a
        - list item b
=== "Markdown"
    ``` md
    === "Tab 1"
        Markdown **content**.

        Multiple paragraphs.

    === "Tab 2"
        More Markdown **content**.

        - list item a
        - list item b
    ```