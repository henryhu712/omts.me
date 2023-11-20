
undefined is dangerous. 在 where 子句中使用 undefined 会返回全部记录！！！

[Clarify null / undefined](https://github.com/prisma/docs/issues/5041)

因此，要排除任何 undefined 的传入，这个工作放到 services 里。

