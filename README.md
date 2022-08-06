# blockchain-developer-bootcampv2

first, run hardhat node locally:
`npx hardhat node `

then, on a separate terminal, deploy scripts:
`npx hardhat run --network localhost ./scripts/1_deploy.js`
make sure the contract address for pengu token, mdai, meth, and exchange
corresponds to the /src/config.json addresses. If not, then copy pasta
the newly deployed local addy

to start react app:
`npm run start`
