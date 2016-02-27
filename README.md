# BEM Light

BEM-style classes contect with one type of separators

## Block

Block is the main unit, block can not be separated.

Examples:

  button
	modal
	bot-dashboard

## Element

Element is the part of the block. Element can not be used out of the block.

Examples:

	button--icon
	modal--header
	bot-dashboard--application

## Modifier

Modifier can be applied to block or element and changes the appearance.

Examples:

	button -size-big -color-grey
	application -expanded

## Prefix

Prefix is a short string in the start of the class name. Similar to namespace in the programming.

Examples:

	v-bot-dashboard (in this case v- means view)
	b-application (in this case b- means block)
