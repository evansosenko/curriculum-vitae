# Curriculum Vitae

[![GitHub Actions](https://github.com/evansosenko/curriculum-vitae/workflows/main/badge.svg)](https://github.com/evansosenko/curriculum-vitae/actions)

The LaTeX source for Evan Sosenko's curriculum vitae.

## Development

### Quickstart

```
$ git clone https://github.com/evansosenko/curriculum-vitae.git
$ cd latex-project
$ npm install
$ make
```

## Requirements

- A modern [LaTeX] distribution, e.g., [TeX Live],
  packaged with [XeLaTeX], [Latexmk], and optionally [ChkTeX].
- [GNU Make].
- [Node.js] with [npm].
  Only required when using Bower for external dependencies.

[ChkTeX]: https://www.nongnu.org/chktex/
[GNU Make]: https://www.gnu.org/software/make/
[LaTeX]: https://www.latex-project.org/
[Latexmk]: https://www.ctan.org/pkg/latexmk/
[Node.js]: https://nodejs.org/
[npm]: https://npmjs.org/
[TeX Live]: https://www.tug.org/texlive/
[XeLaTeX]: https://ctan.org/pkg/xetex

## Development

Install any Node and Bower dependencies with

```
$ npm install
```

Build to `build/` with

```
$ make
```

Clean out temporary and build files with

```
$ make clean
```

Lint code with

```
$ make check
```

Watch code and rebuild on changes with

```
$ npm start
```

## Source Code

The [curriculum-vitae source] is hosted on GitHub.
Clone the project with

```
$ git clone https://github.com/evansosenko/curriculum-vitae.git
```

[curriculum-vitae source]: https://github.com/evansosenko/curriculum-vitae

## Contributing

Please submit and comment on bug reports and feature requests.

To submit a patch:

1. Fork it (https://github.com/evansosenko/curriculum-vitae/fork).
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Make changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin my-new-feature`).
6. Create a new Pull Request.

## License

This LaTeX project is licensed under the MIT license.

## Warranty

This software is provided by the copyright holders and contributors "as is" and
any express or implied warranties, including, but not limited to, the implied
warranties of merchantability and fitness for a particular purpose are
disclaimed. In no event shall the copyright holder or contributors be liable for
any direct, indirect, incidental, special, exemplary, or consequential damages
(including, but not limited to, procurement of substitute goods or services;
loss of use, data, or profits; or business interruption) however caused and on
any theory of liability, whether in contract, strict liability, or tort
(including negligence or otherwise) arising in any way out of the use of this
software, even if advised of the possibility of such damage.
