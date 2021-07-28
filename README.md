# mkdocs-material-search-issue

To illustrate search issue see <https://twitter.com/squidfunk/status/1420453639634685955?s=20>

- Used version 7.1.11

## How to reproduce

- Serve content
  - e.g. `docker run --rm -p 8000:8000 -v ${PWD}:/docs axdotl/mkdocs-material`
- Open <http://localhost:8000>
- Search for `find me`
  - Search result is not shown
  - But located in ./docs/example-chapter/sub-chapter/problematic.md line 15
