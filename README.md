# Refactored_Project_Accesibillity_Upgrade
The purpose of this project was to upgrade the original code to introduce an adequate html semantic structure in order to allow and comply with the accesibllity criteria. 

The method used to achieve what is described above was implementing the proper tags of semantic HTML to devide and specify the content of the website into bloks, according to the criteria and specifications of the client. here is a step by step guide of the refactoring process.

## HTML

* replace the div class= "header" for a header tag. keeping the class already named "header"

* Wihtin the header tag, a nav tag was created for all the navigation buttons/links. this allowed to have a nav section within the header tag.

* Added a figure tag with an alt to describe the background image used in the website.

* The div tag that was enclosing the content was replaced by a main tag.

* All the div elements contained in the div tag mention in the step above were replaced by sections and the broken link was fixed by changing the class for an id in the first img tag within the first section.

* An aside tag was created to create a block of content next to the main tag and all the div tags that were located within the last div were replaced by sections.

* Switched the last div tag for a footer tag.

* Common classes were created for the elements that share the same style atributes, such is the case of the class named "search" within the main tag,"subtitles" within the h2 tag for the sections inside the main tah "common_benefits" within the aside tag, and benefit_subtitles for all the h3 tags contained in the aside tag.

## CSS 

* It was necesary to target the child element nav inside the header tag to keep the styles originally made to those buttons/links.

* The figure tag was targeted without a class or id since it does not requiere one.

* Since a general class named "search" was created to apply all the common styles. (inside the main tag).only one block of code was used targeting such class.

* In order to keep the style of the images within the main tag, it was necesary to target that child element within the class with ".search img"

* the h2 tags shared the same styling atributes so, a general class named "subtitles" was aded to simplify the css code in the aside tag. 

* the same concept explained above was applied to the class named "common_benefit" and "benefit_subtitles. for the section and h3 tags respectively.

* since the img is a child element inside the common_benefit class it was necesary to target it with .common_benefit img in order to keep the syltes given originally.

### ORIGINAL HTML CODE SCREENSHOTS

![image](https://user-images.githubusercontent.com/69653106/95647879-de37e580-0a87-11eb-84dd-66b9cbc5dde9.png)
![image](https://user-images.githubusercontent.com/69653106/95647911-3242ca00-0a88-11eb-949e-e67bfded79d5.png)

### ORIGINAL CSS CODE SCREENSHOTS

![image](https://user-images.githubusercontent.com/69653106/95647952-8057cd80-0a88-11eb-87a8-0fa744cf46a8.png)
![image](https://user-images.githubusercontent.com/69653106/95647973-a9785e00-0a88-11eb-8c46-9b7cba058f1d.png)
![image](https://user-images.githubusercontent.com/69653106/95647994-d75da280-0a88-11eb-82d9-5c028284bf3b.png)
![image](https://user-images.githubusercontent.com/69653106/95648025-0247f680-0a89-11eb-8886-34c312da0e6b.png)

### REFACTORED HTML CODE SCREENSHOTS

![image](https://user-images.githubusercontent.com/69653106/95648122-bc3f6280-0a89-11eb-9103-60f3c78e72d3.png)
![image](https://user-images.githubusercontent.com/69653106/95648152-e6912000-0a89-11eb-8452-9d5bf69d5ac5.png)
![image](https://user-images.githubusercontent.com/69653106/95648186-27893480-0a8a-11eb-8134-966bd32b61c1.png)

### REFACTORED CSS CODE SCREENSHOTS

![image](https://user-images.githubusercontent.com/69653106/95648263-aaaa8a80-0a8a-11eb-9b71-1abc4af86889.png)
![image](https://user-images.githubusercontent.com/69653106/95648283-d0d02a80-0a8a-11eb-86de-b93302d50fc0.png)
![image](https://user-images.githubusercontent.com/69653106/95648297-feb56f00-0a8a-11eb-8367-51ea538328e2.png)
![image](https://user-images.githubusercontent.com/69653106/95648343-345a5800-0a8b-11eb-930e-a50a755695b0.png)

