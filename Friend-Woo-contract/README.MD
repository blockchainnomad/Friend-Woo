hardhat.config.js에서 읽기 위한 .env 파일 생성 후 
API_URL, PRIVATE_KEY, ETHERSCAN_API 값을 입력합니다.

다음 명령어로 컨트랙트를 goerli 이더리움 테스트넷에 배포합니다.

'''
npx hardhat run scripts/run.js --network goerli
'''
