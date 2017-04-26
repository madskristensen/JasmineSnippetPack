# Jasmine Snippet Pack for Visual Studio

[![Build status](https://ci.appveyor.com/api/projects/status/ws4nxf1ypue4xwy3?svg=true)](https://ci.appveyor.com/project/madskristensen/jasminesnippetpack)

Download this extension from the
[VS Gallery](https://visualstudiogallery.msdn.microsoft.com/5d11e28f-0f7c-4f6e-ae50-699fcd5a3500)
or get the
[nightly build](http://vsixgallery.com/extension/4b57f448-ba2e-4404-a0f7-ab1fac14daba/).

-----------------------------------------

A snippet pack to make you more productive working with the
[Jasmine][jasmine] test library. 

This extension contains code snippets for [Jasmine][jasmine] test framework and is based on the awesome [sublime-jasmine][sublime-jusmine] package by [@NicoSantangelo][NicoSantangelo].

![Snippets demo](art/animation.gif)

This extension ships a bunch of useful code snippets for
the JavaScript editor. Get an overview from the
**Code Snippet Manager** in Visual Studio located under
the **Tools** top level menu.

![Snippet manager](art/snippet-manager.png)

## Snippets

Below is a list of all snippets currently supported on this
package and the triggers of each one. The **⇥** means the
`TAB` key.

### Specs
- `describe`: desc⇥
- `xdescribe`: xdesc⇥
- `fdescribe`: fdesc⇥
- `it`: it⇥
- `itd`: itd⇥
- `xit`: xit⇥
- `fit`: fit⇥
- `afterEach`: ae⇥
- `beforeEach`: be⇥

### Expectations
- `expect`: exp⇥
- `expect().toBe`: tb⇥
- `expect().toBeCloseTo`: tbct⇥
- `expect().toBeDefined`: tbd⇥
- `expect().toBeFalsy`: tbf⇥
- `expect().toBeGreaterThan`: tbgt⇥
- `expect().toBeLessThan`: tblt⇥
- `expect().toBeNull`: tbn⇥
- `expect().toBeTruthy`: tbt⇥
- `expect().toBeUndefined`: tbu⇥
- `expect().toContain`: tc⇥
- `expect().toEqual`: te⇥
- `expect().toHaveBeenCalled`: thbc⇥
- `expect().toHaveBeenCalledWith`: thbcw⇥
- `expect().toMatch`: tm⇥
- `expect().toThrow`: tt⇥
- `expect().toThrowError`: tte⇥
- `expect().not.toBe`: nb⇥
- `expect().not.toBeCloseTo`: nct⇥
- `expect().not.toBeDefined`: nd⇥
- `expect().not.toBeFalsy`: nf⇥
- `expect().not.toBeGreaterThan`: ngt⇥
- `expect().not.toBeLessThan`: nlt⇥
- `expect().not.toBeNull`: nn⇥
- `expect().not.toBeTruthy`: nt⇥
- `expect().not.toBeUndefined`: nu⇥
- `expect().not.toContain`: nc⇥
- `expect().not.toEqual`: ne⇥
- `expect().not.toMatch`: nm⇥
- `expect().not.toThrow`: nt⇥
- `jasmine.any`: any⇥
- `jasmine.objectContaining`: oc⇥

### Spies
- `spyOn`: so⇥
- `spyOn.and.callThrough`: sct⇥
- `spyOn.and.callFake`: scf⇥
- `spyOn.and.returnValue`: srv⇥
- `spyOn.and.stub`: ss⇥
- `spyOn.and.throwError`: ste⇥
- `spy.calls.all`: ca⇥
- `spy.calls.allArgs`: caa⇥
- `spy.calls.any`: ca⇥
- `spy.calls.argsFor`: caf⇥
- `spy.calls.count`: cc⇥
- `spy.calls.first`: cf⇥
- `spy.calls.mostRecent`: cmr⇥
- `spy.calls.reset`: cr⇥
- `createSpy`: cs⇥
- `createSpyObj`: cso⇥

## Contribute
Check out the [contribution guidelines](.github/CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)

[jasmine]: http://jasmine.github.io
[sublime-jusmine]: https://github.com/NicoSantangelo/sublime-jasmine
[NicoSantangelo]: https://github.com/NicoSantangelo