# Planning Layout Notes

## Misc

- Can only use CSS Grid (e.g. no Flexbox)

## Element Hierarchy (By CSS Selectors)

- `.container`
  - `.header`
    - `.logo`
    - `.menu`
      - `ul`
        - `li` x 4
  - `.sidebar`
    - `.photo`
    - `.side-content` x 3
  - `.nav`
    - `ul`
      - `li` x 3
  - `.article`
    - `.card` x 12
      - `.title`
      - `p`
  - `.footer`
