# Site Appearance

The design and functionality of a Liferay site can be adjusted and customized through a variety of complementary mechanisms. The following table summarizes and contrasts how certain tasks can be achieved:

| Features                                | Style Books | Page Templates | Themes |
|-----------------------------------------|:-----------:|:--------------:|:------:|
| Embed common fragments/widgets          |             |        ✓       |    ✓   |
| Define common layouts for pages         |             |        ✓       |    ✓   |
| Managed through the UI                  |      ✓      |        ✓       |        |
| Customize styles, spacing, colors, etc. |      ✓      |                |    ✓   |
| Add extra functionality                 |             |                |    ✓   |

## Master Page Templates

Coming soon!
<!-- TODO:

[Screenshot of creating a master page template]

Introduce concept of Master Page Template, as well as other Page Templates (and the distinction between the two). Link to respective articles -->

## Style Books

[Screenshot of creating a style book?]

Introduce Style Books, note a few really general use cases to give the idea. Note that all the levels "above" (page templates, fragments, etc.) all use these in their displays

## Widget/Fragment Appearance

[Maybe show a considerably customized-looking widget/fragment?]

Introductions and links to:
* Fragment customizations
* Collection Display fragment renderers? Any other analogous features for other fragments? (Hopefully not too long of a list)
* Application Display Templates
* Maybe also a reference to the Configuring Fragment Style article

Note that these can be embedded into many of the lower "layers"
* Does that mean order should be reversed? Feels more natural to start with lowest level though, esp. since that puts themes last

### Style Book Token Definitions

Note how they tie into themes as well (depending on them for definitions), possibly? And then maybe link to developer guide articles? (Unless maybe developer guide material is not good to go into for this overview... then perhaps it'd be better to just briefly reference their reliance on the theme and leave it as that, not even with an H3)

## Themes

[Screenshot of page with non-Classic theme?]

Introduce themes, give picture of how they can be highly flexible.

Reference how they tie into all the higher "layers"?

* Fragments/widgets use themes, and can also be embedded within the themes if necessary
* Page templates use themes for styling
* Style books rely on themes for their token definitions

Link to themes overview, possibly to lower level articles within themes hierarchy...
