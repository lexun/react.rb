## 0.2.1
*  Depends on opal `~> 0.6.0`, which accidentally got loosen in previous release

## 0.2.0

*  Deprecating `jsx` helper method in component instance
*  Deprecating `React::Element.new`, use `React.create_element` instead
*  `React::Element` is now toll-free bridge to [ReactElement](http://facebook.github.io/react/docs/glossary.html#react-elements)
*  `React::Element#props` now return a `Hash` rather than a `Native`
*  `React::Element#children` now handling empty child & single child correctly
