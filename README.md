# star-ratio
Stats that matter.
Handy tool to compare javascript open source projects:

[![thumbnail](./docs/thumbnail.png?raw=true)](http://starratio.js.org)

## Testimonials
> ["Very interesting and clever tool to compare JavaScript frameworks"](https://twitter.com/shanselman/status/775956034229678080) - Scott Hanselman

## This client is build with:
- [create-react-app](https://github.com/facebookincubator/create-react-app)
- [react-vis](https://github.com/uber/react-vis)
- [reactable](https://github.com/glittershark/reactable)
- [React Intl](https://github.com/yahoo/react-intl)
- [moment](https://github.com/moment/moment)
- Github [octicons](https://octicons.github.com/) and colors
- [css-loaders](https://github.com/lukehaas/css-loaders)

## How to add the project to chart?
To add the project to chart just add it into [`data.json`](https://github.com/StarRatio/star-ratio/blob/master/docs/data.json) file.

### `data.json` records format:
`{"type":"frontend_framework","user":"angular","repo":"angular.js","package":"angular"},`

- `type` - (optional) category of the project
  Next types can be used:
    - `backend_framework`
    - `bundler`
    - `styles`
    - `language`
    - `testing_framework`
    - `data_visualization`
- `user` - Github user/organization name
- `repo` - Github repository name
- `package` - (optional) npm package name (skiped if same as Github repository name)
