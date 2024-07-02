# Solana Action & Blink

一键部署：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Fankouzu/solana-action&env=RECIPIENT,BASE_AMOUNT,AVATAR,TITLE,DESCRIPTION,NEXT_PUBLIC_AUTHOR&envDescription=Variables%20to%20setup%20your%20own%20information&envLink=https://github.com/Fankouzu/solana-action&project-name=my-blink-donate-action-next&repository-name=my-blink-donate-action-next&demo-title=Solana%20blink%20action&demo-description=A%20solana%20blink%20action%20example%20using%20Next.js&demo-url=https%3A%2F%2Factions.amagi.love%2F&demo-image=https%3A%2F%2Fucarecdn.com%2F078daf34-3a0a-465b-bda8-8b6715ba86bb%2F-%2Fpreview%2F557x851%2F)

在vercel修改环境变量配置

```shell
RECIPIENT="<Your wallet address>"
BASE_AMOUNT=0.1
TITLE="<Your title>"
AVATAR="<Your avatar URL>"
DESCRIPTION="<Your description>"
```

部署成功后，访问https://<你的仓库名>.vercel.com/api/actions/donate 看到json返回结果就代表部署正确，并且核对你输入的环境变量

访问https://dial.to/?action=solana-action%3Ahttps%3A%2F%2F<你的仓库名>.vercel.app%2Fapi%2Factions%2Fdonate 可以看到你的Blink链接