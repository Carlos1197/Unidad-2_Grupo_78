html {
	font-size: 16px;
}

.social-bar {
	position: fixed;
	right: 0;
	top: 35%;
	font-size: 1.5rem;
	display: flex;
	flex-direction: column;
	align-items: flex-end;
	z-index: 100;
}

.icon {
	color: white;
	text-decoration: none;
	padding: .7rem;
	display: flex;
	transition: all .5s;
}

.icon-facebook {
	background: #2E406E;
}

.icon-twitter {
	background: #339DC5;
}

.icon-youtube {
	background: #E83028;
}

.icon-mail4 {
	background: #3F60A5;
}

.icon:first-child {
	border-radius: 1rem 0 0 0;
}

.icon:last-child {
	border-radius: 0 0 0 1rem;
}

.icon:hover {
	padding-right: 3rem;
	border-radius: 1rem 0 0 1rem;
	box-shadow: 0 0 .5rem rgba(0, 0, 0, 0.42);
}
