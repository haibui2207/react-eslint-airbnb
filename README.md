

*<small>Created 10 Oct 2019</small>*

# # Set up ESLint using [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

  
> 1. Install [ESLint](https://www.npmjs.com/package/eslint)

	npm install -s eslint
> 2.  Create ESLint configuration file

	touch .eslintrc.json
 Eslint sample content. See [here](https://github.com/haibui2207/react-eslint-airbnb/blob/master/.eslintrc.json)

# # Integrate Prettier with ESLint
> 1. Install [prettier](https://prettier.io/)

	npm install -s prettier
> 2.  Create eslint configure file

	touch .prettierrc
> 3.  Reference packages

	npm install --save-dev eslint-plugin-import
	npm install --save-dev eslint-config-prettier eslint-plugin-prettier
	npm install --save-dev eslint-config-airbnb
 Prettier sample content. See [here](https://github.com/haibui2207/react-eslint-airbnb/blob/master/.prettierrc)
> 3. Integrate Prettier with ESLint

	npm install - eslint-config-prettier eslint-plugin-prettier

 `eslint-config-prettier` disables rules that conflict with Prettier
 
 `eslint-plugin-prettier` adds the rule that format content using Prettier.

Enable this configuration by using the recommended one

	{
	  "extends": ["plugin:prettier/recommended"]
	}
