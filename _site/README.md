### TM website

Taken from [this github project](https://github.com/evanca/quick-portfolio)

### Setup

#### Prerequisites
- Ruby (tested with 4.0.1)
- Bundler

#### Install dependencies

```bash
bundle install
```

#### Troubleshooting: `eventmachine` build failure on macOS 26+

If `bundle install` fails with `'iostream' file not found` when compiling `eventmachine`, the C++ standard library headers are missing from the compiler's default search path.

Fix by setting the include path before installing:

```bash
CPLUS_INCLUDE_PATH="/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/include/c++/v1" bundle install
```

To make this permanent, add to `~/.zshrc`:

```bash
export CPLUS_INCLUDE_PATH="/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/include/c++/v1"
```

Alternatively, reinstalling Command Line Tools may fix it:

```bash
sudo rm -rf /Library/Developer/CommandLineTools
xcode-select --install
```

#### Run locally

```bash
bundle exec jekyll serve
```