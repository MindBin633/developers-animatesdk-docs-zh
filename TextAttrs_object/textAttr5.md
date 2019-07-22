## textAttrs.characterSpacing

#### Availability

Flash MX 2004. Deprecated in Flash 8 in favor of [textAttrs.letterSpacing](#_bookmark1016).

#### Usage

textAttrs.characterSpacing

#### Description

Property; an integer that represents the space between characters. Acceptable values are -60 through 60. This property applies only to static text; it generates a warning if used with other text types.

#### Example

```javascript
The following example sets the character spacing of the selected text field to 10:
fl.getDocumentDOM().setElementTextAttr("characterSpacing", 10);

```