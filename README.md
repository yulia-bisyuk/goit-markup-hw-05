# goit-markup-hw-05

.list-item .link {
transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.list-item .link:hover,
.list-item .link:focus {
color: var(--accent-color);
}

.icon-mail {
margin-right: 10px;
fill: var(--main-text-color);
}
.link .icon-mail,
.link .icon-phone {
transition: fill 5000ms cubic-bezier(0.4, 0, 0.2, 1);
}

.link:hover .icon-mail,
.link:focus .icon-mail {
fill: var(--accent-color);
}
.icon-phone {
margin-right: 10px;
fill: var(--main-text-color);
}

.link:hover .icon-phone,
.link:focus .icon-phone {
fill: var(--accent-color);
}
