## JWT(JSON WEB TOKEN)

Login을 통해 payload의 정보를 token으로 생성하여 cookie를 통해 client에게 전달하고 페이지 갱신마다 token verification을 통해 expried를 갱신해준다.

## Next step
- DataBase와 서버사이드 connect를 통해 사용자의 정보를 저장한다.
- accessToken과 refreshToken을 생성하여 cookie 헤더에 refreshToken과 accessToken을 전달한다.
- XSS 취약점을 보완할 방법을 찾는다.
