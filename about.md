---
layout: page
permalink: /about.html
title: About
---

As you you already read at the [title page](/), UML .FRI is a CASE
(Computer Aided Software Engineering) tool. The goals of this tool are
a bit different then other CASE tools have. UML .FRI exists primarily
to help computer science teachers in teaching different modeling
languages. I don't say, software engineers are discouraged from using
it if they want. But they are not the target group.

### Design goals (or features if you want)

There are some things I still keep in my mind when designing new
features. You can find some of them here.

* **Easy to use.** Final users of the UML .FRI tool are students (in
  the most cases at least). They are not expected to fight with the tool
  and learn how to overcome any difficulties that came in one package
  with the tool. They should learn some modeling language instead.

* **Easy to extend.** Anyone can extend UML .FRI. That's it. You can
  design your own modeling language, or describe an existing one, and
  UML .FRI will let you to create models in this language. You can
  extend functionality and automate something by creating plugin in
  (hopefully) any programming language.

  The ability to use any modeling language is a bit in contrast with
  having UML in the tool name. The name UML .FRI is heritage from its
  complicated history.

* **Multiplatform.**  I dont't want to force students to use “the only
  one platform I consider to be the best”™. That's why I choose Qt as
  a GUI framework for UML .FRI 2. The old version of the tool used Gtk+
  instead. Gtk+ is a great tool for sure, but the only one platform it
  works that great is (my favorite btw) Linux/X11.

  The new version of UML .FRI (UML .FRI 2.x) nicely integrate into all
  three: Linux, Windows and Mac Os X. I have even some plans to support
  Android/iOS in the future.

* **Free and Open-source.** It is necessary for the tool to stay open.
  I don't want the tool to die with me. If a school adopt the tool
  in its learning process it is important for them to be certain that
  the tool will be developed in a future. If I cannot fulfill my
  responsibilities as a UML .FRI 2.x developer, anyone is guarantied
  to be able to continue the tool development in my stead.

  The tool has to be free as a free beer too. I cannot ask students to
  buy the software if they want to work on their projects at home.

* **Multilanguage.** UML .FRI 2.x has good support for translations.
  Both, GUI and metamodel can be translated to multiple languages.
  The tool tries to use system language settings when possible, but
  user can override autodetected option.
