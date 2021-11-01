# [5.0.0-beta.1](https://github.com/parse-community/parse-server/compare/4.5.0...5.0.0-beta.1) (2021-11-01)


### Bug Fixes

* add deprecation warning for `Parse.Cloud.httpRequest` ([#7595](https://github.com/parse-community/parse-server/issues/7595)) ([ab1dddd](https://github.com/parse-community/parse-server/commit/ab1dddd406589800e1a8ebe8381b9da702e9c641))
* add support for descending sorting of full text search ([#7496](https://github.com/parse-community/parse-server/issues/7496)) ([8ed9442](https://github.com/parse-community/parse-server/commit/8ed94421e69b1d4fde4ec3625a1f4cfbd6d39c2b))
* allow LiveQuery on Parse.Session ([#7554](https://github.com/parse-community/parse-server/issues/7554)) ([caee281](https://github.com/parse-community/parse-server/commit/caee281bc58901fea7cead21d6a9a0bb2022d91b))
* combined `and` query with relational query condition returns incorrect results ([#7593](https://github.com/parse-community/parse-server/issues/7593)) ([174886e](https://github.com/parse-community/parse-server/commit/174886e385e091c6bbd4a84891ef95f80b50d05c))
* empty file tags cause upload error for some providers ([#7300](https://github.com/parse-community/parse-server/issues/7300)) ([4d16702](https://github.com/parse-community/parse-server/commit/4d167026aebed38bf3a3b74599ab3771d1da3245))
* **Logger:** Handle interpolating stdout ([#7114](https://github.com/parse-community/parse-server/issues/7114)) ([1ede078](https://github.com/parse-community/parse-server/commit/1ede078154213d3426cc492612ce41bdb1eda43b))
* improve security by deprecating creating users with public access by default ([#7319](https://github.com/parse-community/parse-server/issues/7319)) ([484c2e8](https://github.com/parse-community/parse-server/commit/484c2e81cace608eb28508a0926b17b3ba9e6233))
* package.json & package-lock.json to reduce vulnerabilities ([#7112](https://github.com/parse-community/parse-server/issues/7112)) ([7b8d8dd](https://github.com/parse-community/parse-server/commit/7b8d8ddbb0de583621a4d2ede95793c6516bc4c0))
* package.json & package-lock.json to reduce vulnerabilities ([#7218](https://github.com/parse-community/parse-server/issues/7218)) ([0476832](https://github.com/parse-community/parse-server/commit/047683219daf7940590db1237f6826a038bdc41d))
* package.json & package-lock.json to reduce vulnerabilities ([#7373](https://github.com/parse-community/parse-server/issues/7373)) ([b6843de](https://github.com/parse-community/parse-server/commit/b6843de904bf273bf664d94536defa39f91751b3))
* package.json & package-lock.json to reduce vulnerabilities ([#7405](https://github.com/parse-community/parse-server/issues/7405)) ([d915bac](https://github.com/parse-community/parse-server/commit/d915bacee7c6ded60b303582d2a6b85d42dc3cf4))
* package.json & package-lock.json to reduce vulnerabilities ([#7423](https://github.com/parse-community/parse-server/issues/7423)) ([bea4707](https://github.com/parse-community/parse-server/commit/bea4707783febc0fc6ea055835ffbc517cd2b067))
* package.json & package-lock.json to reduce vulnerabilities ([#7509](https://github.com/parse-community/parse-server/issues/7509)) ([65c967a](https://github.com/parse-community/parse-server/commit/65c967a4c446aebb535cbbbcb0ceb38d45da7859))
* Pass customObjectId in beforeSave ([#7167](https://github.com/parse-community/parse-server/issues/7167)) ([7224cde](https://github.com/parse-community/parse-server/commit/7224cde0232d79fea0f4b2d0bc2cb7641ec467d8)), closes [#6733](https://github.com/parse-community/parse-server/issues/6733)
* **utils:** permutation helper ([#7355](https://github.com/parse-community/parse-server/issues/7355)) ([91be6bb](https://github.com/parse-community/parse-server/commit/91be6bb59a61c126b7a25431655064342464905c))
* set objects in afterFind triggers ([#7311](https://github.com/parse-community/parse-server/issues/7311)) ([68a3a87](https://github.com/parse-community/parse-server/commit/68a3a875017d545253f0438c5d4c1c2b6c6c3b22))
* setting a field to null does not delete it via GraphQL API ([#7649](https://github.com/parse-community/parse-server/issues/7649)) ([626fad2](https://github.com/parse-community/parse-server/commit/626fad2e71017dcc62196c487de5f908fa43000b))
* upgrade @apollographql/graphql-playground-html from 1.6.26 to 1.6.27 ([#7274](https://github.com/parse-community/parse-server/issues/7274)) ([a05e9b1](https://github.com/parse-community/parse-server/commit/a05e9b1c0fee8ad917812637256faa1e0a1b40f6))
* upgrade @apollographql/graphql-playground-html from 1.6.27 to 1.6.28 ([#7411](https://github.com/parse-community/parse-server/issues/7411)) ([c58bf57](https://github.com/parse-community/parse-server/commit/c58bf57f51ebc9df3a624fb3ecdacdf4647f1dea))
* upgrade @apollographql/graphql-playground-html from 1.6.28 to 1.6.29 ([#7473](https://github.com/parse-community/parse-server/issues/7473)) ([39f7c83](https://github.com/parse-community/parse-server/commit/39f7c831e6493cff9cd64195b64e886fda4624f8))
* upgrade @parse/simple-mailgun-adapter from 1.1.0 to 1.2.0 ([#7109](https://github.com/parse-community/parse-server/issues/7109)) ([8ff0d08](https://github.com/parse-community/parse-server/commit/8ff0d08dcf5a9ada931359df3e78543445312f15))
* upgrade apollo-server-express from 2.19.0 to 2.19.1 ([#7122](https://github.com/parse-community/parse-server/issues/7122)) ([33bdd87](https://github.com/parse-community/parse-server/commit/33bdd8709266f17489c319e43b3f2a7d8ea27fd5))
* upgrade apollo-server-express from 2.19.1 to 2.19.2 ([#7165](https://github.com/parse-community/parse-server/issues/7165)) ([4b6e9ff](https://github.com/parse-community/parse-server/commit/4b6e9ffc3d2c1969c285c94f7cf2cfc7af03227e))
* upgrade apollo-server-express from 2.19.2 to 2.20.0 ([#7239](https://github.com/parse-community/parse-server/issues/7239)) ([d10e990](https://github.com/parse-community/parse-server/commit/d10e99007b70816707944060905cff7da5018eb0))
* upgrade apollo-server-express from 2.21.0 to 2.21.1 ([#7308](https://github.com/parse-community/parse-server/issues/7308)) ([3dc4597](https://github.com/parse-community/parse-server/commit/3dc459746dbd4a2d245f2bde688cd087a5b74703))
* upgrade apollo-server-express from 2.21.1 to 2.22.1 ([#7357](https://github.com/parse-community/parse-server/issues/7357)) ([25690ad](https://github.com/parse-community/parse-server/commit/25690ad515551bda33dd581789ffeb9a218c8033))
* upgrade apollo-server-express from 2.22.1 to 2.22.2 ([#7362](https://github.com/parse-community/parse-server/issues/7362)) ([181fbf9](https://github.com/parse-community/parse-server/commit/181fbf9d46bee61b5c67a411b4a41c38d201cc73))
* upgrade apollo-server-express from 2.22.2 to 2.23.0 ([#7380](https://github.com/parse-community/parse-server/issues/7380)) ([87476da](https://github.com/parse-community/parse-server/commit/87476da31e28e064fa7192998c67de9c31ac18a6))
* upgrade apollo-server-express from 2.23.0 to 2.24.0 ([#7395](https://github.com/parse-community/parse-server/issues/7395)) ([ff5755b](https://github.com/parse-community/parse-server/commit/ff5755b05ac554a107a443a8870f4c2442b0a5f3))
* upgrade apollo-server-express from 2.24.0 to 2.24.1 ([#7424](https://github.com/parse-community/parse-server/issues/7424)) ([bfdb6a9](https://github.com/parse-community/parse-server/commit/bfdb6a93e8c0d78524820b32abaff174776520f3))
* upgrade apollo-server-express from 2.24.1 to 2.25.0 ([#7435](https://github.com/parse-community/parse-server/issues/7435)) ([4e5eba6](https://github.com/parse-community/parse-server/commit/4e5eba6c6c7bc6e643ac6477df15beea1ba60364))
* upgrade apollo-server-express from 2.25.0 to 2.25.1 ([#7449](https://github.com/parse-community/parse-server/issues/7449)) ([682f1bf](https://github.com/parse-community/parse-server/commit/682f1bf14388e134fbd993e274f5738ec2e57e02))
* upgrade apollo-server-express from 2.25.1 to 2.25.2 ([#7465](https://github.com/parse-community/parse-server/issues/7465)) ([1fe4708](https://github.com/parse-community/parse-server/commit/1fe47087a92c80e7ee8cc6e3e26b3a67f8df68ee))
* upgrade follow-redirects from 1.13.0 to 1.13.1 ([#7106](https://github.com/parse-community/parse-server/issues/7106)) ([16b4aad](https://github.com/parse-community/parse-server/commit/16b4aadfe2b5b5b24e6e3bbe22c93a92f02c9eb3))
* upgrade follow-redirects from 1.13.1 to 1.13.2 ([#7194](https://github.com/parse-community/parse-server/issues/7194)) ([738ba9f](https://github.com/parse-community/parse-server/commit/738ba9fc704a770bd1e2af23bca31ed7202f99cd))
* upgrade follow-redirects from 1.13.2 to 1.13.3 ([#7285](https://github.com/parse-community/parse-server/issues/7285)) ([d144819](https://github.com/parse-community/parse-server/commit/d144819d21b59b11dc957346748ce3200349a6b7))
* upgrade follow-redirects from 1.13.3 to 1.14.0 ([#7389](https://github.com/parse-community/parse-server/issues/7389)) ([38c01c6](https://github.com/parse-community/parse-server/commit/38c01c6bc32fe769c3a636e45b389e2a995c2ee6))
* upgrade follow-redirects from 1.14.0 to 1.14.1 ([#7408](https://github.com/parse-community/parse-server/issues/7408)) ([8976ecc](https://github.com/parse-community/parse-server/commit/8976ecc4a9c91eeb1d0f3448eff7720b43c7747a))
* upgrade graphql from 15.4.0 to 15.5.0 ([#7201](https://github.com/parse-community/parse-server/issues/7201)) ([5a09687](https://github.com/parse-community/parse-server/commit/5a0968721d6d04cdde86d3df569a77910bcae803))
* upgrade graphql from 15.5.0 to 15.5.1 ([#7462](https://github.com/parse-community/parse-server/issues/7462)) ([bbd7ee7](https://github.com/parse-community/parse-server/commit/bbd7ee7313e19c43b15e16027439739590393dd1))
* upgrade graphql from 15.5.1 to 15.5.2 ([#7587](https://github.com/parse-community/parse-server/issues/7587)) ([dee4d96](https://github.com/parse-community/parse-server/commit/dee4d9662749eb699891c8a3797fa0b0467c6355))
* upgrade graphql from 15.5.2 to 15.5.3 ([#7596](https://github.com/parse-community/parse-server/issues/7596)) ([bcbc035](https://github.com/parse-community/parse-server/commit/bcbc035627c552a7940bec4ae210ca1522215246))
* upgrade graphql from 15.5.3 to 15.6.0 ([#7612](https://github.com/parse-community/parse-server/issues/7612)) ([407ed6e](https://github.com/parse-community/parse-server/commit/407ed6ee36ea42d7eb525f42b1f3da6f41230504))
* upgrade graphql-relay from 0.6.0 to 0.7.0 ([#7443](https://github.com/parse-community/parse-server/issues/7443)) ([770e36f](https://github.com/parse-community/parse-server/commit/770e36ff43c42e4ed3db73a30436079a0460a1f0))
* upgrade graphql-relay from 0.7.0 to 0.8.0 ([#7467](https://github.com/parse-community/parse-server/issues/7467)) ([9923cd3](https://github.com/parse-community/parse-server/commit/9923cd3869ab80e70c5ca9765628ba0a28a6facc))
* upgrade graphql-tag from 2.10.1 to 2.12.0 ([#7234](https://github.com/parse-community/parse-server/issues/7234)) ([add67fd](https://github.com/parse-community/parse-server/commit/add67fdd2284a58386f6afd35edeaa8534579e33))
* upgrade graphql-tag from 2.12.0 to 2.12.1 ([#7282](https://github.com/parse-community/parse-server/issues/7282)) ([36de1db](https://github.com/parse-community/parse-server/commit/36de1db65dc3c2bbf8f8051ee1862a06ef41e7f9))
* upgrade graphql-tag from 2.12.1 to 2.12.2 ([#7325](https://github.com/parse-community/parse-server/issues/7325)) ([50e5557](https://github.com/parse-community/parse-server/commit/50e55571fdaa1ac3ca43d215c4bc62136d684873))
* upgrade graphql-tag from 2.12.2 to 2.12.4 ([#7396](https://github.com/parse-community/parse-server/issues/7396)) ([8099cb0](https://github.com/parse-community/parse-server/commit/8099cb05a48956b073f3e7d96c30b69292c06adc))
* upgrade graphql-tag from 2.12.4 to 2.12.5 ([#7466](https://github.com/parse-community/parse-server/issues/7466)) ([2b3355c](https://github.com/parse-community/parse-server/commit/2b3355cb022724838499a5d83c0d532040953566))
* upgrade jwks-rsa from 1.11.0 to 1.12.0 ([#7102](https://github.com/parse-community/parse-server/issues/7102)) ([029edbf](https://github.com/parse-community/parse-server/commit/029edbf706c4b1754afbb5ce69600a373b91cb9b))
* upgrade jwks-rsa from 1.12.1 to 1.12.2 ([#7147](https://github.com/parse-community/parse-server/issues/7147)) ([bcb2b52](https://github.com/parse-community/parse-server/commit/bcb2b52f7a1322a780b95b77081827d6c8c25840))
* upgrade jwks-rsa from 1.12.2 to 1.12.3 ([#7284](https://github.com/parse-community/parse-server/issues/7284)) ([a53d74c](https://github.com/parse-community/parse-server/commit/a53d74c13b86d43e1694132feddccce6ee2bede9))
* upgrade ldapjs from 2.2.2 to 2.2.3 ([#7095](https://github.com/parse-community/parse-server/issues/7095)) ([fb465e5](https://github.com/parse-community/parse-server/commit/fb465e599e8768b9e229ec8689e033d7063e50b3))
* upgrade ldapjs from 2.2.3 to 2.2.4 ([#7275](https://github.com/parse-community/parse-server/issues/7275)) ([35f0c55](https://github.com/parse-community/parse-server/commit/35f0c55e93dc0572049a85befbc80175620f7d29))
* upgrade ldapjs from 2.2.4 to 2.3.0 ([#7436](https://github.com/parse-community/parse-server/issues/7436)) ([7df6c02](https://github.com/parse-community/parse-server/commit/7df6c020b18b8ea9d04b718fa4e070be800b9268))
* upgrade ldapjs from 2.3.0 to 2.3.1 ([#7524](https://github.com/parse-community/parse-server/issues/7524)) ([dee5a13](https://github.com/parse-community/parse-server/commit/dee5a13a85336cdd9d3bcd938c4118fffe8b9670))
* upgrade mime from 2.4.6 to 2.4.7 ([#7110](https://github.com/parse-community/parse-server/issues/7110)) ([fefcabe](https://github.com/parse-community/parse-server/commit/fefcabe858f3817dca337390c2198abbf12f9bdf))
* upgrade mime from 2.4.7 to 2.5.0 ([#7166](https://github.com/parse-community/parse-server/issues/7166)) ([6097e82](https://github.com/parse-community/parse-server/commit/6097e82194772847954dc2c2b7559543cc7531cc))
* upgrade mime from 2.5.0 to 2.5.2 ([#7261](https://github.com/parse-community/parse-server/issues/7261)) ([687f4b7](https://github.com/parse-community/parse-server/commit/687f4b7cf245ce578674a4cc0e0d276b23d5780d))
* upgrade mongodb from 3.6.6 to 3.6.7 ([#7425](https://github.com/parse-community/parse-server/issues/7425)) ([61affe2](https://github.com/parse-community/parse-server/commit/61affe26293f7218e88878d027514d68975cfc8c))
* upgrade mongodb from 3.6.7 to 3.6.8 ([#7430](https://github.com/parse-community/parse-server/issues/7430)) ([c36588e](https://github.com/parse-community/parse-server/commit/c36588e3c2d16fab3f38aecc77f0e827bda38f95))
* upgrade mongodb from 3.6.8 to 3.6.9 ([#7445](https://github.com/parse-community/parse-server/issues/7445)) ([17cf1a4](https://github.com/parse-community/parse-server/commit/17cf1a46e557b502b132c415b922508e032209a9))
* upgrade mongodb from 3.6.9 to 3.6.10 ([#7474](https://github.com/parse-community/parse-server/issues/7474)) ([45d29cc](https://github.com/parse-community/parse-server/commit/45d29cc58c373c9e1d489dbd7a750f2a0f6bc89b))
* upgrade mustache from 4.1.0 to 4.2.0 ([#7358](https://github.com/parse-community/parse-server/issues/7358)) ([94b7b32](https://github.com/parse-community/parse-server/commit/94b7b320062579e788df6c9f72d7a786f98f7cc5))
* upgrade parse from 3.1.0 to 3.2.0 ([#7378](https://github.com/parse-community/parse-server/issues/7378)) ([e9f54e2](https://github.com/parse-community/parse-server/commit/e9f54e2bddd8430864b1628ab077a0a3aae73e47))
* upgrade pg-promise from 10.10.1 to 10.10.2 ([#7399](https://github.com/parse-community/parse-server/issues/7399)) ([d365f1f](https://github.com/parse-community/parse-server/commit/d365f1f7cb44cfdeac9931308ff25dcd9ba3d79b))
* upgrade pg-promise from 10.10.2 to 10.11.0 ([#7510](https://github.com/parse-community/parse-server/issues/7510)) ([a967e79](https://github.com/parse-community/parse-server/commit/a967e7921961ea7a33ae9ff02555839cecf2b15f))
* upgrade pg-promise from 10.8.1 to 10.8.6 ([#7118](https://github.com/parse-community/parse-server/issues/7118)) ([8851810](https://github.com/parse-community/parse-server/commit/8851810a85747456cd2f3e5d3876371306b8c23d))
* upgrade pg-promise from 10.8.6 to 10.8.7 ([#7148](https://github.com/parse-community/parse-server/issues/7148)) ([231c669](https://github.com/parse-community/parse-server/commit/231c669133eea494f2db7f23fdff2e9d004c9e18))
* upgrade pg-promise from 10.8.7 to 10.9.0 ([#7168](https://github.com/parse-community/parse-server/issues/7168)) ([fcacd4d](https://github.com/parse-community/parse-server/commit/fcacd4d24e34ff48367d2c68bb97743b8a20216c))
* upgrade pg-promise from 10.9.0 to 10.9.1 ([#7170](https://github.com/parse-community/parse-server/issues/7170)) ([cca493b](https://github.com/parse-community/parse-server/commit/cca493b9fb33a4c34eaaf624ec4aedd18b11dca7))
* upgrade pg-promise from 10.9.1 to 10.9.2 ([#7209](https://github.com/parse-community/parse-server/issues/7209)) ([c05102b](https://github.com/parse-community/parse-server/commit/c05102b90c925498459b45c755298cb482ac596c))
* upgrade redis from 3.1.1 to 3.1.2 ([#7387](https://github.com/parse-community/parse-server/issues/7387)) ([f65bd22](https://github.com/parse-community/parse-server/commit/f65bd228fb3491ba217558ec288dd2ee60d0d37d))
* upgrade semver from 7.3.2 to 7.3.4 ([#7092](https://github.com/parse-community/parse-server/issues/7092)) ([7e687b1](https://github.com/parse-community/parse-server/commit/7e687b1e943372d105ca359177824241af278534))
* upgrade subscriptions-transport-ws from 0.9.19 to 0.10.0 ([#7450](https://github.com/parse-community/parse-server/issues/7450)) ([d36a53b](https://github.com/parse-community/parse-server/commit/d36a53b2bfade99942e3c9b827c9abb38d2de26b))
* upgrade uuid from 8.3.1 to 8.3.2 ([#7101](https://github.com/parse-community/parse-server/issues/7101)) ([f17a063](https://github.com/parse-community/parse-server/commit/f17a063209b451da291918dac165e177f0bee6a0))
* upgrade winston-daily-rotate-file from 4.5.0 to 4.5.1 ([#7309](https://github.com/parse-community/parse-server/issues/7309)) ([8643ae4](https://github.com/parse-community/parse-server/commit/8643ae438f1ea48c93d2860889568f9f3a5a62b8))
* upgrade winston-daily-rotate-file from 4.5.1 to 4.5.2 ([#7376](https://github.com/parse-community/parse-server/issues/7376)) ([e143fb1](https://github.com/parse-community/parse-server/commit/e143fb1bf6a52bb21c483fbf72f74d2282cfbeee))
* upgrade winston-daily-rotate-file from 4.5.2 to 4.5.3 ([#7398](https://github.com/parse-community/parse-server/issues/7398)) ([e9d8ed4](https://github.com/parse-community/parse-server/commit/e9d8ed4acb03160c8f6d669859fe57d8281937b4))
* upgrade winston-daily-rotate-file from 4.5.3 to 4.5.4 ([#7402](https://github.com/parse-community/parse-server/issues/7402)) ([4f80a5f](https://github.com/parse-community/parse-server/commit/4f80a5f4afbc008d2f642ee0c581a25483240e9a))
* upgrade winston-daily-rotate-file from 4.5.4 to 4.5.5 ([#7407](https://github.com/parse-community/parse-server/issues/7407)) ([5abbeeb](https://github.com/parse-community/parse-server/commit/5abbeeb8d11be810993c528b8458be894039a5fc))
* upgrade ws from 7.4.0 to 7.4.1 ([#7098](https://github.com/parse-community/parse-server/issues/7098)) ([1068838](https://github.com/parse-community/parse-server/commit/106883809c96a758bb23ae6dd7fff7465fbd8f60))
* upgrade ws from 7.4.1 to 7.4.2 ([#7132](https://github.com/parse-community/parse-server/issues/7132)) ([857d4ec](https://github.com/parse-community/parse-server/commit/857d4ecfd5a383d6debd849a1af1d45820aee0c0))
* upgrade ws from 7.4.2 to 7.4.3 ([#7224](https://github.com/parse-community/parse-server/issues/7224)) ([ec8f784](https://github.com/parse-community/parse-server/commit/ec8f78424f0043fa74ef1f3a7baa96a3d1e95b59))
* upgrade ws from 7.4.3 to 7.4.4 ([#7298](https://github.com/parse-community/parse-server/issues/7298)) ([a080e4c](https://github.com/parse-community/parse-server/commit/a080e4c766c33cc5b5c304bbdba69e93743f9db1))
* upgrade ws from 7.4.4 to 7.4.5 ([#7381](https://github.com/parse-community/parse-server/issues/7381)) ([34f3dd9](https://github.com/parse-community/parse-server/commit/34f3dd9e7e1908b713355ddb235b1e5d02634663))
* upgrade ws from 7.5.3 to 8.2.1 ([#7580](https://github.com/parse-community/parse-server/issues/7580)) ([c3da290](https://github.com/parse-community/parse-server/commit/c3da2908fabfa4f7f49c0f6d5b3d32de692dd388))
* upgrade ws from 8.2.1 to 8.2.2 ([#7598](https://github.com/parse-community/parse-server/issues/7598)) ([20cb333](https://github.com/parse-community/parse-server/commit/20cb3333aba67fb89e4e2cda586c559bdb4a23ef))

### Features

* add support for Postgres 14 ([#7644](https://github.com/parse-community/parse-server/issues/7644)) ([090350a](https://github.com/parse-community/parse-server/commit/090350a7a0fac945394ca1cb24b290316ef06aa7))
* add user-defined schema and migrations ([#7418](https://github.com/parse-community/parse-server/issues/7418)) ([25d5c30](https://github.com/parse-community/parse-server/commit/25d5c30be2111be332eb779eb0697774a17da7af))
* alphabetical graphql api, fix internal reassign, enhanced Graphql schema cache system ([#7344](https://github.com/parse-community/parse-server/issues/7344)) ([85ef721](https://github.com/parse-community/parse-server/commit/85ef7217b04e36395e46316004293e9c8ca67df9))
* **LiveQuery:** Support $and, $nor, $containedBy, $geoWithin ([#7113](https://github.com/parse-community/parse-server/issues/7113)) ([93781b2](https://github.com/parse-community/parse-server/commit/93781b2195d8074032d2c4dfd77a56acf17dc9e1))
* **AggregateRouter:** support native mongodb syntax in aggregation pipelines ([#7339](https://github.com/parse-community/parse-server/issues/7339)) ([8fddac3](https://github.com/parse-community/parse-server/commit/8fddac39bf866886c3b432219acc4d5e8169ddc0))


### BREAKING CHANGES

* To delete a field via the GraphQL API, the field value has to be set to `null`. Previously, setting a field value to `null` would save a null value in the database, which was not according to the [GraphQL specs](https://spec.graphql.org/June2018/#sec-Null-Value). To delete a file field use `file: null`, the previous way of using `file: { file: null }` has become obsolete. ([626fad2](626fad2))