make a copy of env.sample with the name of environment e.g ganache or moonbeam
final result will be .env.ganache or .env.moonbeam

run following command to specify the environment
> export NODE_ENV=ganache or export NODE_ENV=moonbeam

after that run one of the following commands
> npm run deploy:ganache
> npm run deploy:moonbeam

you may run the following command to have instance of ganache running in your local environment
> npm run ganache