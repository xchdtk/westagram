<h1>westagram<h1>
  instagram에 회원가입, 로그인, 댓글, 팔로우등 다양한 기능을 구현하였습니다

<h2>📲 회원가입</h2> 

email과 password만으로 가능하게 구현하였습니다.

알맞지 않는 값이 들어오거나 그에 맞는 응답을 보내주었습니다.


<h2>📱 로그인</h2>

로그인을 성공하면 access token을 발급하였습니다.

로그인 실패 시 그에 맞는 응답을 보내주었습니다.

<h2>🕹 게시물 등록</h2>

access token을 확인하여 게시물을 사용할 수 있는 지를 데코레이터를 이용해 구현하였습니다.

body에 게시물에 필요한 값을 받아 데이터베이스에 알맞게 저장하였습니다.

<h2>🖱 댓글</h2>

access token을 확인하여 댓글를 사용할 수 있는 지를 데코레이터를 이용해 구현하였습니다.

post_id를 받아서 해당하는 게시물에 댓글을 다는 기능을 구현하였습니다.

<h2>💻 좋아요</h2>
access token을 확인하여 좋아요를 사용할 수 있는 지를 데코레이터를 이용해 구현하였습니다.

post_id를 받아서 해당하는 게시물에 좋아요 기능을 구현하였습니다.

<h2>🖥 follow</h2>
access token을 확인하여 팔로우를 사용할 수 있는 지를 데코레이터를 이용해 구현하였습니다.

access token을 통해 팔로우하는 계정을 알아냈고,  팔로우 할 계정을 받아서 팔로우 기능을 구현하였습니다.

<h2>⌨️ 대댓글</h2>
access token을 확인하여 대댓글을 사용할 수 있는 지를 데코레이터를 이용해 구현하였습니다.

게시물과 게시물에 달린 댓글에 댓글을 다는 기능을 구현하였습니다.
