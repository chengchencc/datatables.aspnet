<h1>Datatables.AspNet</h1>
<p>
	Formely known as <strong>DataTables.Mvc</strong>, this project started over a year ago with small objectives, aiming to provide intermediate and experienced developers a tool to avoid the boring process of handling DataTables parameters.
</p>
<p>
	More than 15 months later, we now undergo a full rewrite with support for Mvc, WebApi and AspNet (<strong>core CLR included!</strong>).<br />
	Also, unit-testing is a priority to avoid breaking <i>your</i> app.
</p>
<h3>NuGet is here!</h3>
<p>
	After many requests, I've released official NuGet packages, which include:
</p>
- [DataTables.AspNet.Mvc5](https://www.nuget.org/packages/DataTables.AspNet.Mvc5/), with support for Mvc5, registration and automatic binders
- [DataTables.AspNet.AspNet5](https://www.nuget.org/packages/DataTables.AspNet.AspNet5/) with support for AspNet5, dependency injection and automatic binders

Or, if you'd like to extend DataTables.AspNet (let's say to enable it on a new tech or provide extensions methods for your ORM of choice) check out [DataTables.AspNet.Core](https://www.nuget.org/packages/DataTables.AspNet.Core/) which contains core elements, including standard interfaces and enums.

<h3>Samples, samples, samples!</h3>
<p>
	Although I've released only very very basic samples (basic integration), they already provide some ideia on what's to come and how to enable DataTables.AspNet on your app. For now, you can check them on 'dev' branch. They will, however, have their own pages on wiki.
</p>
<h3>Eager for some new code?</h3>
<p>
	If you are, check out 'dev' branch. It has the latest code for DataTables.AspNet, including samples and more.<br />
	Be advised that alpha is not production-ready and your should decide carefully before adopting it for your app.
</p>
<h3>Or... maybe go legacy?</h3>
<p>
	If you don't want to (or can't) go alpha, check 'legacy' branch, along with zip releases. They won't be oficially released under NuGet because they've been discontinued.<br />
	Latest zip release includes some pull requests and minor fixes for old DataTables.Mvc.
</p>
<h3>Migration path</h3>
<p>
	Although you'll need to change existing code, by the time DataTables.AspNet reaches beta a full migration path will be released to help with existing code.<br />
	I've chosen <strong>beta</strong> as the "due date" to a migration path because during <i>alpha</i> code might change a lot and building a migration path for that would just be hell.
</p>
