# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `media > type`

```javascript
CSSRoot {
	body: [
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 1:7-1:13
						}
						loc: SourceLocation media/type/input.css 1:6-1:14
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 1:14-1:16
				}
				loc: SourceLocation media/type/input.css 1:6-1:16
			}
			loc: SourceLocation media/type/input.css 1:0-1:16
		}
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						condition: "not"
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 2:11-2:17
						}
						loc: SourceLocation media/type/input.css 2:6-2:18
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 2:18-2:20
				}
				loc: SourceLocation media/type/input.css 2:6-2:20
			}
			loc: SourceLocation media/type/input.css 2:0-2:20
		}
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						condition: "only"
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 3:12-3:18
						}
						loc: SourceLocation media/type/input.css 3:6-3:19
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 3:19-3:21
				}
				loc: SourceLocation media/type/input.css 3:6-3:21
			}
			loc: SourceLocation media/type/input.css 3:0-3:21
		}
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						value: CSSMediaType {
							value: "print"
							loc: SourceLocation media/type/input.css 4:7-4:12
						}
						loc: SourceLocation media/type/input.css 4:6-4:12
					}
					CSSMediaQuery {
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 4:14-4:20
						}
						loc: SourceLocation media/type/input.css 4:14-4:21
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 4:21-4:23
				}
				loc: SourceLocation media/type/input.css 4:6-4:23
			}
			loc: SourceLocation media/type/input.css 4:0-4:23
		}
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 5:7-5:13
						}
						loc: SourceLocation media/type/input.css 5:6-5:13
					}
					CSSMediaQuery {
						value: CSSMediaType {
							value: "all"
							loc: SourceLocation media/type/input.css 5:15-5:18
						}
						loc: SourceLocation media/type/input.css 5:15-5:18
					}
					CSSMediaQuery {
						value: CSSMediaType {
							value: "print"
							loc: SourceLocation media/type/input.css 5:20-5:25
						}
						loc: SourceLocation media/type/input.css 5:20-5:26
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 5:26-5:28
				}
				loc: SourceLocation media/type/input.css 5:6-5:28
			}
			loc: SourceLocation media/type/input.css 5:0-5:28
		}
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						condition: "only"
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation media/type/input.css 6:12-6:18
						}
						loc: SourceLocation media/type/input.css 6:6-6:18
					}
					CSSMediaQuery {
						condition: "not"
						value: CSSMediaType {
							value: "all"
							loc: SourceLocation media/type/input.css 6:24-6:27
						}
						loc: SourceLocation media/type/input.css 6:20-6:27
					}
					CSSMediaQuery {
						condition: "only"
						value: CSSMediaType {
							value: "print"
							loc: SourceLocation media/type/input.css 6:34-6:39
						}
						loc: SourceLocation media/type/input.css 6:29-6:40
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation media/type/input.css 6:40-6:42
				}
				loc: SourceLocation media/type/input.css 6:6-6:42
			}
			loc: SourceLocation media/type/input.css 6:0-6:42
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	path: RelativePath<media/type/input.css>
	loc: SourceLocation media/type/input.css 1:0-6:42
}
```
