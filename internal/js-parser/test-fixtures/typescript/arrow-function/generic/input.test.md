# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > arrow-function > generic`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSArrowFunctionExpression {
				body: JSReferenceIdentifier {
					name: "a"
					loc: SourceLocation typescript/arrow-function/generic/input.ts 1:16-1:17 (a)
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					params: [
						JSBindingIdentifier {
							name: "a"
							meta: JSPatternMeta {
								typeAnnotation: TSTypeReference {
									typeName: JSReferenceIdentifier {
										name: "T"
										loc: SourceLocation typescript/arrow-function/generic/input.ts 1:7-1:8 (T)
									}
									loc: SourceLocation typescript/arrow-function/generic/input.ts 1:7-1:8
								}
								loc: SourceLocation typescript/arrow-function/generic/input.ts 1:16-1:15
							}
							loc: SourceLocation typescript/arrow-function/generic/input.ts 1:16-1:15
						}
					]
					returnType: TSTypeReference {
						typeName: JSReferenceIdentifier {
							name: "T"
							loc: SourceLocation typescript/arrow-function/generic/input.ts 1:11-1:12 (T)
						}
						loc: SourceLocation typescript/arrow-function/generic/input.ts 1:11-1:12
					}
					typeParameters: TSTypeParameterDeclaration {
						params: [
							TSTypeParameter {
								name: "T"
								loc: SourceLocation typescript/arrow-function/generic/input.ts 1:1-1:2
							}
						]
						loc: SourceLocation typescript/arrow-function/generic/input.ts 1:0-1:3
					}
					loc: SourceLocation typescript/arrow-function/generic/input.ts 1:3-1:15
				}
				loc: SourceLocation typescript/arrow-function/generic/input.ts 1:0-1:17
			}
			loc: SourceLocation typescript/arrow-function/generic/input.ts 1:0-1:18
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/arrow-function/generic/input.ts>
	loc: SourceLocation typescript/arrow-function/generic/input.ts 1:0-2:0
}
```

### `diagnostics`

```

```
