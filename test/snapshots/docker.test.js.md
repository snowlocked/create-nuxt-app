# Snapshot report for `test/docker.test.js`

The actual snapshot is saved in `docker.test.js.snap`.

Generated by [AVA](https://ava.li).

## admin

> Generated files

    [
      '.babelrc',
      '.editorconfig',
      '.env',
      '.eslintrc.js',
      '.gitignore',
      '.gitlab-ci.yml',
      '.grenrc.js',
      '.npmignore',
      '.postinstall.sh',
      '.prettierrc',
      '.stylelintrc',
      'README.md',
      'commitlint.config.js',
      'jsconfig.json',
      'nuxt.config.js',
      'package.json',
      'src/api/index.js',
      'src/api/repository.js',
      'src/api/serviceList.js',
      'src/assets/README.md',
      'src/assets/export.less',
      'src/assets/global.less',
      'src/assets/normalize.less',
      'src/assets/svg/logo.svg',
      'src/assets/var.less',
      'src/components/README.md',
      'src/components/breadcrumb/bread-data.js',
      'src/components/breadcrumb/index.vue',
      'src/components/copyright.vue',
      'src/components/go-back.vue',
      'src/components/icon-font.vue',
      'src/components/logo.vue',
      'src/components/menu-item.vue',
      'src/components/route-tab.vue',
      'src/components/sidebar.vue',
      'src/components/svg-icon.vue',
      'src/const/cookie-keys.js',
      'src/const/meta.js',
      'src/const/path.js',
      'src/containers/header.vue',
      'src/containers/module-header.vue',
      'src/containers/module-layout.vue',
      'src/layouts/README.md',
      'src/layouts/blank.vue',
      'src/layouts/default.vue',
      'src/layouts/login.vue',
      'src/middleware/README.md',
      'src/middleware/auth-ssr.js',
      'src/middleware/auth.js',
      'src/middleware/meta.js',
      'src/pages/README.md',
      'src/pages/account/field.vue',
      'src/pages/account/group.vue',
      'src/pages/account/organization.vue',
      'src/pages/account/position.vue',
      'src/pages/account/staff.vue',
      'src/pages/dashboard.vue',
      'src/pages/help.vue',
      'src/pages/index.vue',
      'src/pages/login.vue',
      'src/plugins/README.md',
      'src/plugins/api.js',
      'src/plugins/axios.js',
      'src/plugins/element.js',
      'src/plugins/filters.js',
      'src/plugins/icon-font.js',
      'src/plugins/svg-icon.js',
      'src/static/README.md',
      'src/static/favicon.ico',
      'src/static/icon.png',
      'src/store/README.md',
      'src/store/bread.js',
      'src/store/index.js',
      'src/utils/index.js',
      'test/filters.test.js',
      'test/getRouterBase.test.js',
    ]

> package.json

    {
      authors: [
        'levy <levy9527@qq.com>',
        'Han <xsytby1112@gmail.com>',
        'donaldshen <825870831@qq.com>',
      ],
      browserslist: [
        'defaults',
      ],
      dependencies: {
        '@femessage/el-data-table': 'latest',
        '@femessage/el-form-renderer': 'latest',
        '@femessage/element-ui': 'latest',
        '@femessage/upload-to-ali': 'latest',
        '@femessage/v-img': 'latest',
        '@nuxtjs/axios': '5.9.0',
        '@nuxtjs/dotenv': '1.4.1',
        '@nuxtjs/google-analytics': '2.2.2',
        '@nuxtjs/pwa': '3.0.0-beta.19',
        '@nuxtjs/style-resources': '0.1.2',
        dayjs: '1.8.18',
        dotenv: '6.2.0',
        'js-cookie': '2.2.1',
        less: '3.9.0',
        'less-loader': '4.1.0',
        nuxt: '2.11.0',
      },
      devDependencies: {
        '@babel/core': '7.8.3',
        '@babel/plugin-proposal-nullish-coalescing-operator': '7.8.3',
        '@babel/plugin-proposal-optional-chaining': '7.8.3',
        '@babel/preset-env': '7.8.7',
        '@commitlint/cli': '8.2.0',
        '@commitlint/config-conventional': '8.2.0',
        'babel-eslint': '8.2.6',
        'babel-jest': '24.9.0',
        'cross-env': '5.2.1',
        eslint: '4.19.1',
        'eslint-config-prettier': '6.8.0',
        'eslint-friendly-formatter': '3.0.0',
        'eslint-plugin-jest': '23.1.1',
        'eslint-plugin-prettier': '3.1.2',
        'eslint-plugin-vue': '4.7.1',
        'github-release-notes': '0.17.1',
        husky: '1.3.1',
        jest: '24.9.0',
        'lint-staged': '8.2.1',
        prettier: '1.18.2',
        'standard-version': '6.0.1',
        stylelint: '9.10.1',
        'stylelint-config-standard': '18.3.0',
        'svg-sprite-loader': '^4.1.6',
      },
      engines: {
        npm: '>= 5.2.0',
      },
      husky: {
        hooks: {
          'commit-msg': 'commitlint -e $HUSKY_GIT_PARAMS',
          'post-commit': 'git update-index --again',
          'pre-commit': 'lint-staged',
        },
      },
      jest: {
        moduleNameMapper: {
          '^@/(.*)$': '<rootDir>/src/$1',
          '^~/(.*)$': '<rootDir>/src/$1',
        },
      },
      keywords: [
        'vue',
        'nuxt',
        'admin',
        'dashboard',
        'element-ui',
      ],
      'lint-staged': {
        '*.{js,vue}': [
          'eslint --fix',
          'git add',
        ],
        '*.{md,json}': [
          'prettier --write',
          'git add',
        ],
        '*.{vue,less}': [
          'stylelint --fix',
          'git add',
        ],
      },
      private: true,
      scripts: {
        build: 'cross-env MODE=prod nuxt build',
        dev: 'cross-env MODE=dev nuxt',
        'dev:nologin': 'cross-env MODE=dev NO_LOGIN=1 nuxt',
        lint: 'eslint "src/**/*.@(js|vue)" --fix && stylelint src/**/*.{vue,less} --fix',
        mock: 'cross-env MODE=mock nuxt',
        'mock:nologin': 'cross-env MODE=mock NO_LOGIN=1 nuxt',
        preinstall: 'sh ./.postinstall.sh',
        release: 'gren release --override',
        start: 'cross-env HOST=0.0.0.0 PORT=3333 MODE=prod nuxt start',
        stdver: 'standard-version -m \'[skip ci] chore(release): v%s\'',
        test: 'jest',
      },
    }

## mobile

> Generated files

    [
      '.babelrc',
      '.editorconfig',
      '.eslintrc.js',
      '.gitignore',
      '.gitlab-ci.yml',
      '.grenrc.js',
      '.npmignore',
      '.postinstall.sh',
      '.prettierrc',
      '.stylelintrc',
      'README.md',
      'commitlint.config.js',
      'jsconfig.json',
      'nuxt.config.js',
      'package.json',
      'postcss.config.js',
      'src/api/index.js',
      'src/api/repository.js',
      'src/api/serviceList.js',
      'src/assets/README.md',
      'src/assets/global.less',
      'src/assets/icon.png',
      'src/assets/normalize.less',
      'src/assets/var.less',
      'src/components/README.md',
      'src/components/agreement.vue',
      'src/components/copyright.vue',
      'src/components/header-nav-bar.vue',
      'src/components/icon-font.vue',
      'src/components/logo.vue',
      'src/const/cookie-keys.js',
      'src/const/meta.js',
      'src/const/path.js',
      'src/layouts/README.md',
      'src/layouts/default.vue',
      'src/layouts/layout-with-footer.vue',
      'src/layouts/login.vue',
      'src/middleware/README.md',
      'src/middleware/auth-ssr.js',
      'src/middleware/auth.js',
      'src/middleware/meta.js',
      'src/pages/README.md',
      'src/pages/cart.vue',
      'src/pages/goods-detail.vue',
      'src/pages/index.vue',
      'src/pages/login.vue',
      'src/pages/my.vue',
      'src/pages/order-list.vue',
      'src/plugins/README.md',
      'src/plugins/api.js',
      'src/plugins/axios.js',
      'src/plugins/filters.js',
      'src/plugins/icon-font.js',
      'src/plugins/vant.js',
      'src/static/README.md',
      'src/static/favicon.ico',
      'src/static/icon.png',
      'src/store/README.md',
      'src/store/index.js',
      'src/utils/index.js',
      'test/filters.test.js',
      'test/getRouterBase.test.js',
    ]

> package.json

    {
      authors: [
        'levy <levy9527@qq.com>',
        'Han <xsytby1112@gmail.com>',
        'donaldshen <825870831@qq.com>',
      ],
      browserslist: [
        'defaults',
      ],
      dependencies: {
        '@femessage/data-list': 'latest',
        '@femessage/upload-to-ali': 'latest',
        '@femessage/v-img': 'latest',
        '@femessage/vant': 'latest',
        '@nuxtjs/axios': '5.9.0',
        '@nuxtjs/dotenv': '1.4.1',
        '@nuxtjs/google-analytics': '2.2.2',
        '@nuxtjs/pwa': '3.0.0-beta.19',
        '@nuxtjs/style-resources': '0.1.2',
        dayjs: '1.8.18',
        dotenv: '6.2.0',
        'js-cookie': '2.2.1',
        less: '3.9.0',
        'less-loader': '4.1.0',
        nuxt: '2.11.0',
      },
      devDependencies: {
        '@babel/core': '7.8.3',
        '@babel/plugin-proposal-nullish-coalescing-operator': '7.8.3',
        '@babel/plugin-proposal-optional-chaining': '7.8.3',
        '@babel/preset-env': '7.8.7',
        '@commitlint/cli': '8.2.0',
        '@commitlint/config-conventional': '8.2.0',
        'babel-eslint': '8.2.6',
        'babel-jest': '24.9.0',
        'babel-plugin-import': '1.13.0',
        'cross-env': '5.2.1',
        eslint: '4.19.1',
        'eslint-config-prettier': '6.8.0',
        'eslint-friendly-formatter': '3.0.0',
        'eslint-plugin-jest': '23.1.1',
        'eslint-plugin-prettier': '3.1.2',
        'eslint-plugin-vue': '4.7.1',
        'github-release-notes': '0.17.1',
        husky: '1.3.1',
        jest: '24.9.0',
        'lint-staged': '8.2.1',
        'postcss-px-to-viewport': '1.1.1',
        prettier: '1.18.2',
        'standard-version': '6.0.1',
        stylelint: '9.10.1',
        'stylelint-config-standard': '18.3.0',
      },
      engines: {
        npm: '>= 5.2.0',
      },
      husky: {
        hooks: {
          'commit-msg': 'commitlint -e $HUSKY_GIT_PARAMS',
          'post-commit': 'git update-index --again',
          'pre-commit': 'lint-staged',
        },
      },
      jest: {
        moduleNameMapper: {
          '^@/(.*)$': '<rootDir>/src/$1',
          '^~/(.*)$': '<rootDir>/src/$1',
        },
      },
      keywords: [
        'vue',
        'nuxt',
        'vant',
      ],
      'lint-staged': {
        '*.{js,vue}': [
          'eslint --fix',
          'git add',
        ],
        '*.{md,json}': [
          'prettier --write',
          'git add',
        ],
        '*.{vue,less}': [
          'stylelint --fix',
          'git add',
        ],
      },
      private: true,
      scripts: {
        build: 'cross-env MODE=prod nuxt build',
        dev: 'cross-env MODE=dev nuxt',
        'dev:nologin': 'cross-env MODE=dev NO_LOGIN=1 nuxt',
        lint: 'eslint "src/**/*.@(js|vue)" --fix && stylelint src/**/*.{vue,less} --fix',
        mock: 'cross-env MODE=mock nuxt',
        'mock:nologin': 'cross-env MODE=mock NO_LOGIN=1 nuxt',
        preinstall: 'sh ./.postinstall.sh',
        release: 'gren release --override',
        start: 'cross-env HOST=0.0.0.0 PORT=3333 MODE=prod nuxt start',
        stdver: 'standard-version -m \'[skip ci] chore(release): v%s\'',
        test: 'jest',
      },
    }