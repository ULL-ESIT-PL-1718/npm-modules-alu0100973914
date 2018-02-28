# Practice 3 of PL: NPM modules
## Combined repository
In this practice we learned to create **combined repositories** with the command:
```bash
	git submodule
```
We created a combined repository conformed by the repository of the package and the repository of the client which tests it's installation, and checks if the package publication was succesfull.
* [Repository containing the package sources](https://github.com/ULL-ESIT-PL-1718/oop-alu0100973914.git)
* [Testing repository](https://github.com/ULL-ESIT-PL-1718/prueba-oop-alu0100973914.git)

## Package publication
The other objective to achieve was the publication of our package (developed for the last practice)  in npm site. After establishing properly the **package.json** file and login in via command line we could execute the next command to publish our package:
```bash
	npm publish --access=public
```
* [Published package:@alu0100973914/oop](https://www.npmjs.com/package/@alu0100973914/oop)
