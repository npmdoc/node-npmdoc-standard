# api documentation for  [standard (v9.0.2)](http://standardjs.com)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-standard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-standard)
#### JavaScript Standard Style

[![NPM](https://nodei.co/npm/standard.png?downloads=true)](https://www.npmjs.com/package/standard)

[![apidoc](https://npmdoc.github.io/node-npmdoc-standard/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-standard_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-standard/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-standard/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "email": "feross@feross.org",
        "url": "http://feross.org/"
    },
    "bin": {
        "standard": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/feross/standard/issues"
    },
    "dependencies": {
        "eslint": "~3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-config-standard-jsx": "3.3.0",
        "eslint-plugin-promise": "~3.4.0",
        "eslint-plugin-react": "~6.9.0",
        "eslint-plugin-standard": "~2.0.1",
        "standard-engine": "~5.4.0"
    },
    "description": "JavaScript Standard Style",
    "devDependencies": {
        "babel-eslint": "^7.0.0",
        "cross-spawn": "^5.0.1",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "run-parallel-limit": "^1.0.3",
        "standard-packages": "^3.1.9",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9bd3b9467492e212b1914d78553943ff9b48fd99",
        "tarball": "https://registry.npmjs.org/standard/-/standard-9.0.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "ba16c406846893e8da9460170bb8f62ad9ef602c",
    "homepage": "http://standardjs.com",
    "keywords": [
        "JavaScript Standard Style",
        "check",
        "checker",
        "code",
        "code checker",
        "code linter",
        "code standards",
        "code style",
        "enforce",
        "eslint",
        "hint",
        "jscs",
        "jshint",
        "lint",
        "policy",
        "quality",
        "simple",
        "standard",
        "standard style",
        "style",
        "style checker",
        "style linter",
        "verify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bret",
            "email": "bcomnes@gmail.com"
        },
        {
            "name": "dcousens",
            "email": "email@dcousens.com"
        },
        {
            "name": "dcposch",
            "email": "dcposch@dcpos.ch"
        },
        {
            "name": "feross",
            "email": "feross@feross.org"
        },
        {
            "name": "flet",
            "email": "flettre@gmail.com"
        },
        {
            "name": "jb55",
            "email": "bill@casarin.me"
        },
        {
            "name": "jprichardson",
            "email": "jprichardson@gmail.com"
        },
        {
            "name": "linusu",
            "email": "linus@folkdatorn.se"
        },
        {
            "name": "mafintosh",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        },
        {
            "name": "othiym23",
            "email": "ogd@aoaioxxysz.net"
        },
        {
            "name": "reggi",
            "email": "thomas@reggi.com"
        },
        {
            "name": "rstacruz",
            "email": "dropbox@ricostacruz.com"
        },
        {
            "name": "timoxley",
            "email": "secoif@gmail.com"
        },
        {
            "name": "watson",
            "email": "w@tson.dk"
        },
        {
            "name": "xjamundx",
            "email": "jamund@gmail.com"
        },
        {
            "name": "yoshuawuyts",
            "email": "i@yoshuawuyts.com"
        }
    ],
    "name": "standard",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/standard.git"
    },
    "scripts": {
        "test": "./bin/cmd.js --verbose && tape test/*.js",
        "test-disabled": "npm test -- --disabled",
        "test-offline": "npm test -- --offline",
        "test-offline-quick": "npm test -- --offline --quick",
        "test-quick": "npm test -- --quick",
        "update-authors": "./bin/update-authors.sh"
    },
    "version": "9.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module standard](#apidoc.module.standard)
1.  [function <span class="apidocSignatureSpan">standard.</span>eslint.CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine)
1.  [function <span class="apidocSignatureSpan">standard.</span>eslint.RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester)
1.  [function <span class="apidocSignatureSpan">standard.</span>eslint.SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode)
1.  object <span class="apidocSignatureSpan">standard.</span>eslint
1.  object <span class="apidocSignatureSpan">standard.</span>eslint.CLIEngine.prototype
1.  object <span class="apidocSignatureSpan">standard.</span>eslint.RuleTester.prototype
1.  object <span class="apidocSignatureSpan">standard.</span>eslint.SourceCode.prototype
1.  object <span class="apidocSignatureSpan">standard.</span>eslint.linter
1.  object <span class="apidocSignatureSpan">standard.</span>eslintConfig
1.  string <span class="apidocSignatureSpan">standard.</span>cmd

#### [module standard.eslint](#apidoc.module.standard.eslint)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode)
1.  object <span class="apidocSignatureSpan">standard.eslint.</span>linter

#### [module standard.eslint.CLIEngine](#apidoc.module.standard.eslint.CLIEngine)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine.CLIEngine)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>getErrorResults (results)](#apidoc.element.standard.eslint.CLIEngine.getErrorResults)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>getFormatter (format)](#apidoc.element.standard.eslint.CLIEngine.getFormatter)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>outputFixes (report)](#apidoc.element.standard.eslint.CLIEngine.outputFixes)
1.  string <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>version

#### [module standard.eslint.CLIEngine.prototype](#apidoc.module.standard.eslint.CLIEngine.prototype)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>addPlugin (name, pluginobject)](#apidoc.element.standard.eslint.CLIEngine.prototype.addPlugin)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>constructor (options)](#apidoc.element.standard.eslint.CLIEngine.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>executeOnFiles (patterns)](#apidoc.element.standard.eslint.CLIEngine.prototype.executeOnFiles)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>executeOnText (text, filename, warnIgnored)](#apidoc.element.standard.eslint.CLIEngine.prototype.executeOnText)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>getConfigForFile (filePath)](#apidoc.element.standard.eslint.CLIEngine.prototype.getConfigForFile)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>getFormatter (format)](#apidoc.element.standard.eslint.CLIEngine.prototype.getFormatter)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>isPathIgnored (filePath)](#apidoc.element.standard.eslint.CLIEngine.prototype.isPathIgnored)
1.  [function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>resolveFileGlobPatterns (patterns)](#apidoc.element.standard.eslint.CLIEngine.prototype.resolveFileGlobPatterns)

#### [module standard.eslint.RuleTester](#apidoc.module.standard.eslint.RuleTester)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester.RuleTester)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>describe (text, method)](#apidoc.element.standard.eslint.RuleTester.describe)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>getDefaultConfig ()](#apidoc.element.standard.eslint.RuleTester.getDefaultConfig)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>it (text, method)](#apidoc.element.standard.eslint.RuleTester.it)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>resetDefaultConfig ()](#apidoc.element.standard.eslint.RuleTester.resetDefaultConfig)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>setDefaultConfig (config)](#apidoc.element.standard.eslint.RuleTester.setDefaultConfig)

#### [module standard.eslint.RuleTester.prototype](#apidoc.module.standard.eslint.RuleTester.prototype)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.prototype.</span>defineRule (name, rule)](#apidoc.element.standard.eslint.RuleTester.prototype.defineRule)
1.  [function <span class="apidocSignatureSpan">standard.eslint.RuleTester.prototype.</span>run (ruleName, rule, test)](#apidoc.element.standard.eslint.RuleTester.prototype.run)

#### [module standard.eslint.SourceCode](#apidoc.module.standard.eslint.SourceCode)
1.  [function <span class="apidocSignatureSpan">standard.eslint.</span>SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode.SourceCode)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.</span>splitLines (text)](#apidoc.element.standard.eslint.SourceCode.splitLines)

#### [module standard.eslint.SourceCode.prototype](#apidoc.module.standard.eslint.SourceCode.prototype)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>constructor (text, ast)](#apidoc.element.standard.eslint.SourceCode.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getAllComments ()](#apidoc.element.standard.eslint.SourceCode.prototype.getAllComments)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getComments (node)](#apidoc.element.standard.eslint.SourceCode.prototype.getComments)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getIndexFromLoc (loc)](#apidoc.element.standard.eslint.SourceCode.prototype.getIndexFromLoc)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getJSDocComment (node)](#apidoc.element.standard.eslint.SourceCode.prototype.getJSDocComment)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getLines ()](#apidoc.element.standard.eslint.SourceCode.prototype.getLines)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getLocFromIndex (index)](#apidoc.element.standard.eslint.SourceCode.prototype.getLocFromIndex)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getNodeByRangeIndex (index)](#apidoc.element.standard.eslint.SourceCode.prototype.getNodeByRangeIndex)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getText (node, beforeCount, afterCount)](#apidoc.element.standard.eslint.SourceCode.prototype.getText)
1.  [function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>isSpaceBetweenTokens (first, second)](#apidoc.element.standard.eslint.SourceCode.prototype.isSpaceBetweenTokens)

#### [module standard.eslint.linter](#apidoc.module.standard.eslint.linter)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defaults ()](#apidoc.element.standard.eslint.linter.defaults)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defineRule (ruleId, ruleModule)](#apidoc.element.standard.eslint.linter.defineRule)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defineRules (rulesToDefine)](#apidoc.element.standard.eslint.linter.defineRules)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getAllComments (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getAllComments)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getAncestors ()](#apidoc.element.standard.eslint.linter.getAncestors)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getComments (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getComments)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getDeclaredVariables (node)](#apidoc.element.standard.eslint.linter.getDeclaredVariables)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFilename ()](#apidoc.element.standard.eslint.linter.getFilename)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getFirstToken)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getFirstTokens)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getJSDocComment)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getLastToken (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getLastToken)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getLastTokens)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getNodeByRangeIndex)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getRules ()](#apidoc.element.standard.eslint.linter.getRules)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getScope ()](#apidoc.element.standard.eslint.linter.getScope)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSource (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getSource)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSourceCode ()](#apidoc.element.standard.eslint.linter.getSourceCode)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getSourceLines)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenAfter)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenBefore)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenByRangeStart)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokens)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensAfter)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensBefore)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensBetween)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>markVariableAsUsed (name)](#apidoc.element.standard.eslint.linter.markVariableAsUsed)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>report (ruleId, severity, node, location, message, opts, fix, meta)](#apidoc.element.standard.eslint.linter.report)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>reset ()](#apidoc.element.standard.eslint.linter.reset)
1.  [function <span class="apidocSignatureSpan">standard.eslint.linter.</span>verify (textOrSourceCode, config, filenameOrOptions, saveState)](#apidoc.element.standard.eslint.linter.verify)
1.  number <span class="apidocSignatureSpan">standard.eslint.linter.</span>_maxListeners
1.  string <span class="apidocSignatureSpan">standard.eslint.linter.</span>version



# <a name="apidoc.module.standard"></a>[module standard](#apidoc.module.standard)

#### <a name="apidoc.element.standard.eslint.CLIEngine"></a>[function <span class="apidocSignatureSpan">standard.</span>eslint.CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester"></a>[function <span class="apidocSignatureSpan">standard.</span>eslint.RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester)
- description and source-code
```javascript
function RuleTester(testerConfig) {

<span class="apidocCodeCommentSpan">    /**
     * The configuration to use for this tester. Combination of the tester
     * configuration and the default configuration.
     * @type {Object}
     */
</span>    this.testerConfig = lodash.merge(

        // we have to clone because merge uses the first argument for recipient
        lodash.cloneDeep(defaultConfig),
        testerConfig
    );

    /**
     * Rule definitions to define before tests.
     * @type {Object}
     */
    this.rules = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode"></a>[function <span class="apidocSignatureSpan">standard.</span>eslint.SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint"></a>[module standard.eslint](#apidoc.module.standard.eslint)

#### <a name="apidoc.element.standard.eslint.CLIEngine"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester)
- description and source-code
```javascript
function RuleTester(testerConfig) {

<span class="apidocCodeCommentSpan">    /**
     * The configuration to use for this tester. Combination of the tester
     * configuration and the default configuration.
     * @type {Object}
     */
</span>    this.testerConfig = lodash.merge(

        // we have to clone because merge uses the first argument for recipient
        lodash.cloneDeep(defaultConfig),
        testerConfig
    );

    /**
     * Rule definitions to define before tests.
     * @type {Object}
     */
    this.rules = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.CLIEngine"></a>[module standard.eslint.CLIEngine](#apidoc.module.standard.eslint.CLIEngine)

#### <a name="apidoc.element.standard.eslint.CLIEngine.CLIEngine"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>CLIEngine (options)](#apidoc.element.standard.eslint.CLIEngine.CLIEngine)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.getErrorResults"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>getErrorResults (results)](#apidoc.element.standard.eslint.CLIEngine.getErrorResults)
- description and source-code
```javascript
getErrorResults = function (results) {
    const filtered = [];

    results.forEach(result => {
        const filteredMessages = result.messages.filter(isErrorMessage);

        if (filteredMessages.length > 0) {
            filtered.push(
                Object.assign(result, {
                    messages: filteredMessages,
                    errorCount: filteredMessages.length,
                    warningCount: 0
                })
            );
        }
    });

    return filtered;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.getFormatter"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>getFormatter (format)](#apidoc.element.standard.eslint.CLIEngine.getFormatter)
- description and source-code
```javascript
getFormatter = function (format) {

    let formatterPath;

    // default is stylish
    format = format || "stylish";

    // only strings are valid formatters
    if (typeof format === "string") {

        // replace \ with / for Windows compatibility
        format = format.replace(/\\/g, "/");

        // if there's a slash, then it's a file
        if (format.indexOf("/") > -1) {
            const cwd = this.options ? this.options.cwd : process.cwd();

            formatterPath = path.resolve(cwd, format);
        } else {
            formatterPath = './formatters/${format}';
        }

        try {
            return require(formatterPath);
        } catch (ex) {
            ex.message = 'There was a problem loading formatter: ${formatterPath}\nError: ${ex.message}';
            throw ex;
        }

    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.outputFixes"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.</span>outputFixes (report)](#apidoc.element.standard.eslint.CLIEngine.outputFixes)
- description and source-code
```javascript
outputFixes = function (report) {
    report.results.filter(result => result.hasOwnProperty("output")).forEach(result => {
        fs.writeFileSync(result.filePath, result.output);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.CLIEngine.prototype"></a>[module standard.eslint.CLIEngine.prototype](#apidoc.module.standard.eslint.CLIEngine.prototype)

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.addPlugin"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>addPlugin (name, pluginobject)](#apidoc.element.standard.eslint.CLIEngine.prototype.addPlugin)
- description and source-code
```javascript
addPlugin(name, pluginobject) {
    Plugins.define(name, pluginobject);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.constructor"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>constructor (options)](#apidoc.element.standard.eslint.CLIEngine.prototype.constructor)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.executeOnFiles"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>executeOnFiles (patterns)](#apidoc.element.standard.eslint.CLIEngine.prototype.executeOnFiles)
- description and source-code
```javascript
executeOnFiles(patterns) {
    const results = [],
        options = this.options,
        fileCache = this._fileCache,
        configHelper = new Config(options);
    let prevConfig; // the previous configuration used

<span class="apidocCodeCommentSpan">    /**
     * Calculates the hash of the config file used to validate a given file
     * @param  {string} filename The path of the file to retrieve a config object for to calculate the hash
     * @returns {string}         the hash of the config
     */
</span>    function hashOfConfigFor(filename) {
        const config = configHelper.getConfig(filename);

        if (!prevConfig) {
            prevConfig = {};
        }

        // reuse the previously hashed config if the config hasn't changed
        if (prevConfig.config !== config) {

            /*
             * config changed so we need to calculate the hash of the config
             * and the hash of the plugins being used
             */
            prevConfig.config = config;

            const eslintVersion = pkg.version;

            prevConfig.hash = hash('${eslintVersion}_${stringify(config)}');
        }

        return prevConfig.hash;
    }

    /**
     * Executes the linter on a file defined by the 'filename'. Skips
     * unsupported file extensions and any files that are already linted.
     * @param {string} filename The resolved filename of the file to be linted
     * @param {boolean} warnIgnored always warn when a file is ignored
     * @returns {void}
     */
    function executeOnFile(filename, warnIgnored) {
        let hashOfConfig,
            descriptor;

        if (warnIgnored) {
            results.push(createIgnoreResult(filename, options.cwd));
            return;
        }

        if (options.cache) {

            /*
             * get the descriptor for this file
             * with the metadata and the flag that determines if
             * the file has changed
             */
            descriptor = fileCache.getFileDescriptor(filename);
            const meta = descriptor.meta || {};

            hashOfConfig = hashOfConfigFor(filename);

            const changed = descriptor.changed || meta.hashOfConfig !== hashOfConfig;

            if (!changed) {
                debug('Skipping file since hasn't changed: ${filename}');

                /*
                 * Add the the cached results (always will be 0 error and
                 * 0 warnings). We should not cache results for files that
                 * failed, in order to guarantee that next execution will
                 * process those files as well.
                 */
                results.push(descriptor.meta.results);

                // move to the next file
                return;
            }
        } else {
            fileCache.destroy();
        }

        debug('Processing ${filename}');

        const res = processFile(filename, configHelper, options);

        if (options.cache) {

            /*
             * if a file contains errors or warnings we don't want to
             * store the file in the cache so we can guarantee that
             * next execution will also operate on this file
             */
            if (res.errorCount > 0 || res.warningCount > 0) {
                debug('File has problems, skipping it: ${filename}');

                // remove the entry from the cache
                fileCache.removeEntry(filename);
            } else {

                /*
                 * since the file passed we store the result here
                 * TODO: check this as we might not need to store the
                 * successful runs as it will always should be 0 errors and
                 * 0 warnings.
                 */
                descriptor.meta.hashOfConfig = hashOfConfig;
                descriptor.meta.results = res;
            }
        }

        results.push(res);
    }

    const startTime = Date.now();



    patterns = this.resolveFileGlobPatterns(patterns);
    const fileList = globUtil.listFilesToProcess(patterns, options);

    fileList.forEach(fileInfo => {
        executeOnFile(fileInfo.filename, fileInfo ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.executeOnText"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>executeOnText (text, filename, warnIgnored)](#apidoc.element.standard.eslint.CLIEngine.prototype.executeOnText)
- description and source-code
```javascript
executeOnText(text, filename, warnIgnored) {

    const results = [],
        options = this.options,
        configHelper = new Config(options),
        ignoredPaths = new IgnoredPaths(options);

    // resolve filename based on options.cwd (for reporting, ignoredPaths also resolves)
    if (filename && !path.isAbsolute(filename)) {
        filename = path.resolve(options.cwd, filename);
    }

    if (filename && ignoredPaths.contains(filename)) {
        if (warnIgnored) {
            results.push(createIgnoreResult(filename, options.cwd));
        }
    } else {
        results.push(processText(text, configHelper, filename, options.fix, options.allowInlineConfig));
    }

    const stats = calculateStatsPerRun(results);

    return {
        results,
        errorCount: stats.errorCount,
        warningCount: stats.warningCount
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.getConfigForFile"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>getConfigForFile (filePath)](#apidoc.element.standard.eslint.CLIEngine.prototype.getConfigForFile)
- description and source-code
```javascript
getConfigForFile(filePath) {
    const configHelper = new Config(this.options);

    return configHelper.getConfig(filePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.getFormatter"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>getFormatter (format)](#apidoc.element.standard.eslint.CLIEngine.prototype.getFormatter)
- description and source-code
```javascript
getFormatter = function (format) {

    let formatterPath;

    // default is stylish
    format = format || "stylish";

    // only strings are valid formatters
    if (typeof format === "string") {

        // replace \ with / for Windows compatibility
        format = format.replace(/\\/g, "/");

        // if there's a slash, then it's a file
        if (format.indexOf("/") > -1) {
            const cwd = this.options ? this.options.cwd : process.cwd();

            formatterPath = path.resolve(cwd, format);
        } else {
            formatterPath = './formatters/${format}';
        }

        try {
            return require(formatterPath);
        } catch (ex) {
            ex.message = 'There was a problem loading formatter: ${formatterPath}\nError: ${ex.message}';
            throw ex;
        }

    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.isPathIgnored"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>isPathIgnored (filePath)](#apidoc.element.standard.eslint.CLIEngine.prototype.isPathIgnored)
- description and source-code
```javascript
isPathIgnored(filePath) {
    const resolvedPath = path.resolve(this.options.cwd, filePath);
    const ignoredPaths = new IgnoredPaths(this.options);

    return ignoredPaths.contains(resolvedPath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.CLIEngine.prototype.resolveFileGlobPatterns"></a>[function <span class="apidocSignatureSpan">standard.eslint.CLIEngine.prototype.</span>resolveFileGlobPatterns (patterns)](#apidoc.element.standard.eslint.CLIEngine.prototype.resolveFileGlobPatterns)
- description and source-code
```javascript
resolveFileGlobPatterns(patterns) {
    return globUtil.resolveFileGlobPatterns(patterns, this.options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.RuleTester"></a>[module standard.eslint.RuleTester](#apidoc.module.standard.eslint.RuleTester)

#### <a name="apidoc.element.standard.eslint.RuleTester.RuleTester"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>RuleTester (testerConfig)](#apidoc.element.standard.eslint.RuleTester.RuleTester)
- description and source-code
```javascript
function RuleTester(testerConfig) {

<span class="apidocCodeCommentSpan">    /**
     * The configuration to use for this tester. Combination of the tester
     * configuration and the default configuration.
     * @type {Object}
     */
</span>    this.testerConfig = lodash.merge(

        // we have to clone because merge uses the first argument for recipient
        lodash.cloneDeep(defaultConfig),
        testerConfig
    );

    /**
     * Rule definitions to define before tests.
     * @type {Object}
     */
    this.rules = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.describe"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>describe (text, method)](#apidoc.element.standard.eslint.RuleTester.describe)
- description and source-code
```javascript
function defaultHandler(text, method) {
    return method.apply(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.getDefaultConfig"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>getDefaultConfig ()](#apidoc.element.standard.eslint.RuleTester.getDefaultConfig)
- description and source-code
```javascript
getDefaultConfig = function () {
    return defaultConfig;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.it"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>it (text, method)](#apidoc.element.standard.eslint.RuleTester.it)
- description and source-code
```javascript
function defaultHandler(text, method) {
    return method.apply(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.resetDefaultConfig"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>resetDefaultConfig ()](#apidoc.element.standard.eslint.RuleTester.resetDefaultConfig)
- description and source-code
```javascript
resetDefaultConfig = function () {
    defaultConfig = lodash.cloneDeep(testerDefaultConfig);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.setDefaultConfig"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.</span>setDefaultConfig (config)](#apidoc.element.standard.eslint.RuleTester.setDefaultConfig)
- description and source-code
```javascript
setDefaultConfig = function (config) {
    if (typeof config !== "object") {
        throw new Error("RuleTester.setDefaultConfig: config must be an object");
    }
    defaultConfig = config;

    // Make sure the rules object exists since it is assumed to exist later
    defaultConfig.rules = defaultConfig.rules || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.RuleTester.prototype"></a>[module standard.eslint.RuleTester.prototype](#apidoc.module.standard.eslint.RuleTester.prototype)

#### <a name="apidoc.element.standard.eslint.RuleTester.prototype.defineRule"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.prototype.</span>defineRule (name, rule)](#apidoc.element.standard.eslint.RuleTester.prototype.defineRule)
- description and source-code
```javascript
defineRule(name, rule) {
    this.rules[name] = rule;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.RuleTester.prototype.run"></a>[function <span class="apidocSignatureSpan">standard.eslint.RuleTester.prototype.</span>run (ruleName, rule, test)](#apidoc.element.standard.eslint.RuleTester.prototype.run)
- description and source-code
```javascript
run(ruleName, rule, test) {

    const testerConfig = this.testerConfig,
        requiredScenarios = ["valid", "invalid"],
        scenarioErrors = [],
        result = {};

    if (lodash.isNil(test) || typeof test !== "object") {
        throw new Error('Test Scenarios for rule ${ruleName} : Could not find test scenario object');
    }

    requiredScenarios.forEach(scenarioType => {
        if (lodash.isNil(test[scenarioType])) {
            scenarioErrors.push('Could not find any ${scenarioType} test scenarios');
        }
    });

    if (scenarioErrors.length > 0) {
        throw new Error([
            'Test Scenarios for rule ${ruleName} is invalid:'
        ].concat(scenarioErrors).join("\n"));
    }

<span class="apidocCodeCommentSpan">    /* eslint-disable no-shadow */
</span>
    /**
     * Run the rule for the given item
     * @param {string} ruleName name of the rule
     * @param {string|Object} item Item to run the rule against
     * @returns {Object} Eslint run result
     * @private
     */
    function runRuleForItem(ruleName, item) {
        let config = lodash.cloneDeep(testerConfig),
            code, filename, beforeAST, afterAST;

        if (typeof item === "string") {
            code = item;
        } else {
            code = item.code;

            // Assumes everything on the item is a config except for the
            // parameters used by this tester
            const itemConfig = lodash.omit(item, RuleTesterParameters);

            // Create the config object from the tester config and this item
            // specific configurations.
            config = lodash.merge(
                config,
                itemConfig
            );
        }

        if (item.filename) {
            filename = item.filename;
        }

        if (item.options) {
            const options = item.options.concat();

            options.unshift(1);
            config.rules[ruleName] = options;
        } else {
            config.rules[ruleName] = 1;
        }

        eslint.defineRule(ruleName, rule);

        const schema = validator.getRuleOptionsSchema(ruleName);

        if (schema) {
            validateSchema(schema);

            if (validateSchema.errors) {
                throw new Error([
                    'Schema for rule ${ruleName} is invalid:'
                ].concat(validateSchema.errors.map(error => '\t${error.field}: ${error.message}')).join("\n"));
            }
        }

        validator.validate(config, "rule-tester");

        /*
         * Setup AST getters.
         * The goal is to check whether or not AST was modified when
         * running the rule under test.
         */
        eslint.reset();

        eslint.on("Program", node => {
            beforeAST = cloneDeeplyExcludesParent(node);
        });

        eslint.on("Program:exit", node => {
            afterAST = node;
        });

        // Freezes rule-context properties.
        const originalGet = rules.get;

        try {
            rules.get = function(ruleId) {
                const rule = originalGet(ruleId);

                if (typeof rule === "function") {
                    return function(context) {
                        Object.freeze(context);
                        freezeDeeply(context.options);
                        freezeDeeply(context.settings);
                        freezeDeeply(context.parserOptions);

                        return rule(context);
                    };
                }
                return {
                    meta: rule.meta,
                    create(context) {
                        Object.freeze(context);
                        freezeDeeply(context.options);
                        freezeDeeply(context.settings);
                        freezeDeeply(context.parserOptions);

                        return rule.create(context);
                    }
                };

            };

            return {
                messages: eslint.verify(code, config, filename, true),
                beforeAST,
                afterAST: cloneDeeplyExcludesParent(afterAST)
            };
        } finally { ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.SourceCode"></a>[module standard.eslint.SourceCode](#apidoc.module.standard.eslint.SourceCode)

#### <a name="apidoc.element.standard.eslint.SourceCode.SourceCode"></a>[function <span class="apidocSignatureSpan">standard.eslint.</span>SourceCode (text, ast)](#apidoc.element.standard.eslint.SourceCode.SourceCode)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.splitLines"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.</span>splitLines (text)](#apidoc.element.standard.eslint.SourceCode.splitLines)
- description and source-code
```javascript
splitLines = function (text) {
    return text.split(astUtils.createGlobalLinebreakMatcher());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.SourceCode.prototype"></a>[module standard.eslint.SourceCode.prototype](#apidoc.module.standard.eslint.SourceCode.prototype)

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.constructor"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>constructor (text, ast)](#apidoc.element.standard.eslint.SourceCode.prototype.constructor)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getAllComments"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getAllComments ()](#apidoc.element.standard.eslint.SourceCode.prototype.getAllComments)
- description and source-code
```javascript
getAllComments() {
    return this.ast.comments;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getComments"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getComments (node)](#apidoc.element.standard.eslint.SourceCode.prototype.getComments)
- description and source-code
```javascript
getComments(node) {

    let leadingComments = node.leadingComments || [];
    const trailingComments = node.trailingComments || [];

<span class="apidocCodeCommentSpan">    /*
     * espree adds a "comments" array on Program nodes rather than
     * leadingComments/trailingComments. Comments are only left in the
     * Program node comments array if there is no executable code.
     */
</span>    if (node.type === "Program") {
        if (node.body.length === 0) {
            leadingComments = node.comments;
        }
    }

    return {
        leading: leadingComments,
        trailing: trailingComments
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getIndexFromLoc"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getIndexFromLoc (loc)](#apidoc.element.standard.eslint.SourceCode.prototype.getIndexFromLoc)
- description and source-code
```javascript
getIndexFromLoc(loc) {
    if (typeof loc !== "object" || typeof loc.line !== "number" || typeof loc.column !== "number") {
        throw new TypeError("Expected 'loc' to be an object with numeric 'line' and 'column' properties.");
    }

    if (loc.line <= 0) {
        throw new RangeError('Line number out of range (line ${loc.line} requested). Line numbers should be 1-based.');
    }

    if (loc.line > this.lineStartIndices.length) {
        throw new RangeError('Line number out of range (line ${loc.line} requested, but only ${this.lineStartIndices.length} lines
 present).');
    }

    const lineStartIndex = this.lineStartIndices[loc.line - 1];
    const lineEndIndex = loc.line === this.lineStartIndices.length ? this.text.length : this.lineStartIndices[loc.line];
    const positionIndex = lineStartIndex + loc.column;

<span class="apidocCodeCommentSpan">    /*
     * By design, getIndexFromLoc({ line: lineNum, column: 0 }) should return the start index of
     * the given line, provided that the line number is valid element of this.lines. Since the
     * last element of this.lines is an empty string for files with trailing newlines, add a
     * special case where getting the index for the first location after the end of the file
     * will return the length of the file, rather than throwing an error. This allows rules to
     * use getIndexFromLoc consistently without worrying about edge cases at the end of a file.
     */
</span>    if (
        loc.line === this.lineStartIndices.length && positionIndex > lineEndIndex ||
        loc.line < this.lineStartIndices.length && positionIndex >= lineEndIndex
    ) {
        throw new RangeError('Column number out of range (column ${loc.column} requested, but the length of line ${loc.line} is ${
lineEndIndex - lineStartIndex}).');
    }

    return positionIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getJSDocComment"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getJSDocComment (node)](#apidoc.element.standard.eslint.SourceCode.prototype.getJSDocComment)
- description and source-code
```javascript
getJSDocComment(node) {

    let parent = node.parent;

    switch (node.type) {
        case "ClassDeclaration":
        case "FunctionDeclaration":
            if (looksLikeExport(parent)) {
                return findJSDocComment(parent.leadingComments, parent.loc.start.line);
            }
            return findJSDocComment(node.leadingComments, node.loc.start.line);

        case "ClassExpression":
            return findJSDocComment(parent.parent.leadingComments, parent.parent.loc.start.line);

        case "ArrowFunctionExpression":
        case "FunctionExpression":

            if (parent.type !== "CallExpression" && parent.type !== "NewExpression") {
                while (parent && !parent.leadingComments && !/Function/.test(parent.type) && parent.type !== "MethodDefinition" &&
parent.type !== "Property") {
                    parent = parent.parent;
                }

                return parent && (parent.type !== "FunctionDeclaration") ? findJSDocComment(parent.leadingComments, parent.loc.start
.line) : null;
            } else if (node.leadingComments) {
                return findJSDocComment(node.leadingComments, node.loc.start.line);
            }

        // falls through

        default:
            return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getLines"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getLines ()](#apidoc.element.standard.eslint.SourceCode.prototype.getLines)
- description and source-code
```javascript
getLines() {
    return this.lines;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getLocFromIndex"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getLocFromIndex (index)](#apidoc.element.standard.eslint.SourceCode.prototype.getLocFromIndex)
- description and source-code
```javascript
getLocFromIndex(index) {
    if (typeof index !== "number") {
        throw new TypeError("Expected 'index' to be a number.");
    }

    if (index < 0 || index > this.text.length) {
        throw new RangeError('Index out of range (requested index ${index}, but source text has length ${this.text.length}).');
    }

<span class="apidocCodeCommentSpan">    /*
     * For an argument of this.text.length, return the location one "spot" past the last character
     * of the file. If the last character is a linebreak, the location will be column 0 of the next
     * line; otherwise, the location will be in the next column on the same line.
     *
     * See getIndexFromLoc for the motivation for this special case.
     */
</span>    if (index === this.text.length) {
        return { line: this.lines.length, column: this.lines[this.lines.length - 1].length };
    }

    /*
     * To figure out which line rangeIndex is on, determine the last index at which rangeIndex could
     * be inserted into lineIndices to keep the list sorted.
     */
    const lineNumber = lodash.sortedLastIndex(this.lineStartIndices, index);

    return { line: lineNumber, column: index - this.lineStartIndices[lineNumber - 1] };

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getNodeByRangeIndex"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getNodeByRangeIndex (index)](#apidoc.element.standard.eslint.SourceCode.prototype.getNodeByRangeIndex)
- description and source-code
```javascript
getNodeByRangeIndex(index) {
    let result = null,
        resultParent = null;
    const traverser = new Traverser();

    traverser.traverse(this.ast, {
        enter(node, parent) {
            if (node.range[0] <= index && index < node.range[1]) {
                result = node;
                resultParent = parent;
            } else {
                this.skip();
            }
        },
        leave(node) {
            if (node === result) {
                this.break();
            }
        }
    });

    return result ? Object.assign({ parent: resultParent }, result) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.getText"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>getText (node, beforeCount, afterCount)](#apidoc.element.standard.eslint.SourceCode.prototype.getText)
- description and source-code
```javascript
getText(node, beforeCount, afterCount) {
    if (node) {
        return this.text.slice(Math.max(node.range[0] - (beforeCount || 0), 0),
            node.range[1] + (afterCount || 0));
    }
    return this.text;


}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.SourceCode.prototype.isSpaceBetweenTokens"></a>[function <span class="apidocSignatureSpan">standard.eslint.SourceCode.prototype.</span>isSpaceBetweenTokens (first, second)](#apidoc.element.standard.eslint.SourceCode.prototype.isSpaceBetweenTokens)
- description and source-code
```javascript
isSpaceBetweenTokens(first, second) {
    const text = this.text.slice(first.range[1], second.range[0]);

    return /\s/.test(text.replace(/\/\*.*?\*\//g, ""));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.standard.eslint.linter"></a>[module standard.eslint.linter](#apidoc.module.standard.eslint.linter)

#### <a name="apidoc.element.standard.eslint.linter.defaults"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defaults ()](#apidoc.element.standard.eslint.linter.defaults)
- description and source-code
```javascript
defaults = function () {
    return require("../conf/eslint-recommended");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.defineRule"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defineRule (ruleId, ruleModule)](#apidoc.element.standard.eslint.linter.defineRule)
- description and source-code
```javascript
defineRule = function (ruleId, ruleModule) {
    rules.define(ruleId, ruleModule);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.defineRules"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>defineRules (rulesToDefine)](#apidoc.element.standard.eslint.linter.defineRules)
- description and source-code
```javascript
defineRules = function (rulesToDefine) {
    Object.getOwnPropertyNames(rulesToDefine).forEach(ruleId => {
        defineRule(ruleId, rulesToDefine[ruleId]);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getAllComments"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getAllComments (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getAllComments)
- description and source-code
```javascript
getAllComments = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getAncestors"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getAncestors ()](#apidoc.element.standard.eslint.linter.getAncestors)
- description and source-code
```javascript
getAncestors = function () {
    return traverser.parents();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getComments"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getComments (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getComments)
- description and source-code
```javascript
getComments = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getDeclaredVariables"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getDeclaredVariables (node)](#apidoc.element.standard.eslint.linter.getDeclaredVariables)
- description and source-code
```javascript
getDeclaredVariables = function (node) {
    return (scopeManager && scopeManager.getDeclaredVariables(node)) || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getFilename"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFilename ()](#apidoc.element.standard.eslint.linter.getFilename)
- description and source-code
```javascript
getFilename = function () {
    if (typeof currentFilename === "string") {
        return currentFilename;
    }
    return "<input>";

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getFirstToken"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getFirstToken)
- description and source-code
```javascript
getFirstToken = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getFirstTokens"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getFirstTokens)
- description and source-code
```javascript
getFirstTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getJSDocComment"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getJSDocComment)
- description and source-code
```javascript
getJSDocComment = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getLastToken"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getLastToken (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getLastToken)
- description and source-code
```javascript
getLastToken = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getLastTokens"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getLastTokens)
- description and source-code
```javascript
getLastTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getNodeByRangeIndex"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getNodeByRangeIndex)
- description and source-code
```javascript
getNodeByRangeIndex = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getRules"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getRules ()](#apidoc.element.standard.eslint.linter.getRules)
- description and source-code
```javascript
getRules = function () {
    return rules.getAllLoadedRules();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getScope"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getScope ()](#apidoc.element.standard.eslint.linter.getScope)
- description and source-code
```javascript
getScope = function () {
    const parents = traverser.parents();

    // Don't do this for Program nodes - they have no parents
    if (parents.length) {

        // if current node introduces a scope, add it to the list
        const current = traverser.current();

        if (currentConfig.parserOptions.ecmaVersion >= 6) {
            if (["BlockStatement", "SwitchStatement", "CatchClause", "FunctionDeclaration", "FunctionExpression", "ArrowFunctionExpression
"].indexOf(current.type) >= 0) {
                parents.push(current);
            }
        } else {
            if (["FunctionDeclaration", "FunctionExpression", "ArrowFunctionExpression"].indexOf(current.type) >= 0) {
                parents.push(current);
            }
        }

        // Ascend the current node's parents
        for (let i = parents.length - 1; i >= 0; --i) {

            // Get the innermost scope
            const scope = scopeManager.acquire(parents[i], true);

            if (scope) {
                if (scope.type === "function-expression-name") {
                    return scope.childScopes[0];
                }
                return scope;

            }

        }

    }

    return currentScopes[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getSource"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSource (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getSource)
- description and source-code
```javascript
getSource = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getSourceCode"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSourceCode ()](#apidoc.element.standard.eslint.linter.getSourceCode)
- description and source-code
```javascript
getSourceCode = function () {
    return sourceCode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getSourceLines"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getSourceLines)
- description and source-code
```javascript
getSourceLines = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokenAfter"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenAfter)
- description and source-code
```javascript
getTokenAfter = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokenBefore"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenBefore)
- description and source-code
```javascript
getTokenBefore = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokenByRangeStart"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokenByRangeStart)
- description and source-code
```javascript
getTokenByRangeStart = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokens"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokens (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokens)
- description and source-code
```javascript
getTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokensAfter"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensAfter)
- description and source-code
```javascript
getTokensAfter = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokensBefore"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensBefore)
- description and source-code
```javascript
getTokensBefore = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.getTokensBetween"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.standard.eslint.linter.getTokensBetween)
- description and source-code
```javascript
getTokensBetween = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.markVariableAsUsed"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>markVariableAsUsed (name)](#apidoc.element.standard.eslint.linter.markVariableAsUsed)
- description and source-code
```javascript
markVariableAsUsed = function (name) {
    const hasGlobalReturn = currentConfig.parserOptions.ecmaFeatures && currentConfig.parserOptions.ecmaFeatures.globalReturn,
        specialScope = hasGlobalReturn || currentConfig.parserOptions.sourceType === "module";
    let scope = this.getScope(),
        i,
        len;

    // Special Node.js scope means we need to start one level deeper
    if (scope.type === "global" && specialScope) {
        scope = scope.childScopes[0];
    }

    do {
        const variables = scope.variables;

        for (i = 0, len = variables.length; i < len; i++) {
            if (variables[i].name === name) {
                variables[i].eslintUsed = true;
                return true;
            }
        }
    } while ((scope = scope.upper));

    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.report"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>report (ruleId, severity, node, location, message, opts, fix, meta)](#apidoc.element.standard.eslint.linter.report)
- description and source-code
```javascript
report = function (ruleId, severity, node, location, message, opts, fix, meta) {
    if (node) {
        assert.strictEqual(typeof node, "object", "Node must be an object");
    }

    if (typeof location === "string") {
        assert.ok(node, "Node must be provided when reporting error if location is not provided");

        meta = fix;
        fix = opts;
        opts = message;
        message = location;
        location = node.loc.start;
    }

    // Store end location.
    const endLocation = location.end;

    location = location.start || location;

    if (isDisabledByReportingConfig(reportingConfig, ruleId, location)) {
        return;
    }

    if (opts) {
        message = message.replace(/\{\{\s*([^{}]+?)\s*\}\}/g, (fullMatch, term) => {
            if (term in opts) {
                return opts[term];
            }

            // Preserve old behavior: If parameter name not provided, don't replace it.
            return fullMatch;
        });
    }

    const problem = {
        ruleId,
        severity,
        message,
        line: location.line,
        column: location.column + 1,   // switch to 1-base instead of 0-base
        nodeType: node && node.type,
        source: sourceCode.lines[location.line - 1] || ""
    };

    // Define endLine and endColumn if exists.
    if (endLocation) {
        problem.endLine = endLocation.line;
        problem.endColumn = endLocation.column + 1;   // switch to 1-base instead of 0-base
    }

    // ensure there's range and text properties, otherwise it's not a valid fix
    if (fix && Array.isArray(fix.range) && (typeof fix.text === "string")) {

        // If rule uses fix, has metadata, but has no metadata.fixable, we should throw
        if (meta && !meta.fixable) {
            throw new Error("Fixable rules should export a 'meta.fixable' property.");
        }

        problem.fix = fix;
    }

    messages.push(problem);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.reset"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>reset ()](#apidoc.element.standard.eslint.linter.reset)
- description and source-code
```javascript
reset = function () {
    this.removeAllListeners();
    messages = [];
    currentConfig = null;
    currentScopes = null;
    scopeManager = null;
    traverser = null;
    reportingConfig = [];
    sourceCode = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.standard.eslint.linter.verify"></a>[function <span class="apidocSignatureSpan">standard.eslint.linter.</span>verify (textOrSourceCode, config, filenameOrOptions, saveState)](#apidoc.element.standard.eslint.linter.verify)
- description and source-code
```javascript
verify = function (textOrSourceCode, config, filenameOrOptions, saveState) {
    const text = (typeof textOrSourceCode === "string") ? textOrSourceCode : null;
    let ast,
        parseResult,
        shebang,
        allowInlineConfig;

    // evaluate arguments
    if (typeof filenameOrOptions === "object") {
        currentFilename = filenameOrOptions.filename;
        allowInlineConfig = filenameOrOptions.allowInlineConfig;
        saveState = filenameOrOptions.saveState;
    } else {
        currentFilename = filenameOrOptions;
    }

    if (!saveState) {
        this.reset();
    }

    // search and apply "eslint-env *".
    const envInFile = findEslintEnv(text || textOrSourceCode.text);

    if (envInFile) {
        if (!config || !config.env) {
            config = Object.assign({}, config || {}, { env: envInFile });
        } else {
            config = Object.assign({}, config);
            config.env = Object.assign({}, config.env, envInFile);
        }
    }

    // process initial config to make it safe to extend
    config = prepareConfig(config || {});

    // only do this for text
    if (text !== null) {

        // there's no input, just exit here
        if (text.trim().length === 0) {
            sourceCode = new SourceCode(text, blankScriptAST);
            return messages;
        }

        parseResult = parse(
            stripUnicodeBOM(text).replace(/^#!([^\r\n]+)/, (match, captured) => {
                shebang = captured;
                return '//${captured}';
            }),
            config,
            currentFilename
        );

        // if this result is from a parseForESLint() method, normalize
        if (parseResult && parseResult.ast) {
            ast = parseResult.ast;
        } else {
            ast = parseResult;
            parseResult = null;
        }

        if (ast) {
            sourceCode = new SourceCode(text, ast);
        }

    } else {
        sourceCode = textOrSourceCode;
        ast = sourceCode.ast;
    }

    // if espree failed to parse the file, there's no sense in setting up rules
    if (ast) {

        // parse global comments and modify config
        if (allowInlineConfig !== false) {
            config = modifyConfigsFromComments(currentFilename, ast, config, reportingConfig, messages);
        }

        // ensure that severities are normalized in the config
        ConfigOps.normalize(config);

        // enable appropriate rules
        Object.keys(config.rules).filter(key => getRuleSeverity(config.rules[key]) > 0).forEach(key => {
            let ruleCreator;

            ruleCreator = rules.get(key);

            if (!ruleCreator) {
                const replacementMsg = getRuleReplacementMessage(key);

                if (replacementMsg) {
                    ruleCreator = createStubRule(replacementMsg);
                } else {
                    ruleCreator = createStubRule('Definition for rule '${key}' was not found');
                }
                rules.define(key, ruleCreator);
            }

            const severity = getRuleSeverity(config.rules[key]);
            const options = getRuleOptions(config.rules[key]);

            try {
                const ruleContext = new RuleContext(
                    key, api, severity, options,
                    config.settings, config.parserOptions, config.parser,
                    ruleCreator.meta,
                    (parseResult && parseResult.services ? parseResult.services : {})
                );

                const rule = ruleCreator.create ? ruleCreator.create(ruleContext)
                    : ruleCreator(ruleContext);

                // add all the selectors from the rule as listeners
                Object.keys(rule).forEach(selector => {
                    api.on(selector, timing.enabled
                        ? timing.time(key, rule[selector])
                        : rule[selector]
                    );
                });
            } catch (ex) {
                ex.message = 'Error while loading rule '${key}': ${ex.message}';
                throw ex;
            } ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
