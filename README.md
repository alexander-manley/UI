# UI
Embedded UI

REACT

NODEJS


package.json
{
  "dependencies": {
    "jspm": "^0.16.33",
    "karma": "^1.1.2",
    "karma-jspm": "^2.1.1",
    "karma-mocha": "^1.0.1",
    "karma-phantomjs-launcher": "^1.0.0",
    "mocha": "^2.5.3",
    "nib": "^1.1.0",
    "phantomjs-prebuilt": "^2.1.7",
    "shonkwrap": "^1.3.0",
    "stylint": "^1.3.10",
    "stylus": "^0.54.5",
    "tslint": "^3.11.0",
    "typings": "^1.0.4"
  },
  "jspm": {
    "dependencies": {
      "bytebuffer": "github:dcodeIO/bytebuffer.js@^5.0.1",
      "classnames": "npm:classnames@^2.2.5",
      "css": "github:systemjs/plugin-css@^0.1.23",
      "d3": "npm:d3@^3.5.17",
      "es6-promise": "npm:es6-promise@^3.2.1",
      "lodash": "npm:lodash@^4.14.0",
      "long": "npm:long@^3.2.0",
      "moment": "npm:moment@^2.14.1",
      "nvd3": "npm:nvd3@^1.8.4",
      "protobufjs": "npm:protobufjs@^5.0.1",
      "react": "npm:react@^15.2.1",
      "react-dom": "npm:react-dom@^15.2.1",
      "react-paginate": "npm:react-paginate@^2.1.3",
      "react-redux": "npm:react-redux@^4.4.5",
      "react-router": "npm:react-router@^2.6.0",
      "react-router-redux": "npm:react-router-redux@^4.0.5",
      "redux": "npm:redux@^3.5.2",
      "redux-thunk": "npm:redux-thunk@^2.1.0",
      "reselect": "npm:reselect@^2.5.3",
      "whatwg-fetch": "github:tamird/fetch@support-arraybuffer"
    },
    "devDependencies": {
      "chai": "npm:chai@^3.5.0",
      "enzyme": "npm:enzyme@^2.4.1",
      "fetch-mock": "npm:fetch-mock@^5.0.3",
      "react-addons-test-utils": "npm:react-addons-test-utils@^15.2.1",
      "sinon": "npm:sinon@^1.17.4",
      "ts": "github:frankwallis/plugin-typescript@^5.0.8",
      "ts-runtime": "npm:babel-runtime@^6.9.2"
    },
    "overrides": {
      "npm:enzyme@2.3.0": {
        "map": {
          "react/addons": "@empty",
          "react/lib/ExecutionEnvironment": "@empty",
          "react/lib/ReactContext": "@empty"
        }
      },
      "npm:moment@2.13.0": {
        "files": [
          "moment.js",
          "moment.d.ts",
          "locale"
        ]
      }
    }
  }
}





****

typings.json
{
  "globalDependencies": {
    "bytebuffer": "registry:dt/bytebuffer#5.0.0+20160624071349",
    "classnames": "registry:dt/classnames#0.0.0+20160316155526",
    "cockroach-protos": "file:generated/protos.d.ts",
    "es6-promise": "registry:dt/es6-promise#0.0.0+20160614011821",
    "fetch-mock": "registry:dt/fetch-mock#5.0.0+20160724065250",
    "long": "registry:dt/long#3.0.2+20160602144319",
    "mocha": "registry:dt/mocha#2.2.5+20160720003353",
    "react": "registry:dt/react#0.14.0+20160805125551",
    "react-dom": "registry:dt/react-dom#0.14.0+20160412154040",
    "react-redux": "registry:dt/react-redux#4.4.0+20160720003245",
    "whatwg-fetch": "registry:dt/whatwg-fetch#0.0.0+20160728142841"
  },
  "dependencies": {
    "chai": "registry:npm/chai#3.5.0+20160723033700",
    "d3": "registry:npm/d3#3.0.0+20160723033700",
    "enzyme": "registry:npm/enzyme#2.2.0+20160322031343",
    "lodash": "registry:npm/lodash#4.0.0+20160723033700",
    "nvd3": "registry:npm/nvd3#1.8.3+20160711175044",
    "protos-builders": "file:app/js/protos.d.ts",
    "react-paginate": "file:local_typings/react-paginate.d.ts",
    "react-router": "registry:npm/react-router#2.4.0+20160803174347",
    "react-router-redux": "registry:npm/react-router-redux#4.0.0+20160602212457",
    "redux-thunk": "registry:npm/redux-thunk#2.0.0+20160525185520",
    "sinon": "registry:npm/sinon#1.16.0+20160723033700"
  }
}
