# Rails Mini Project

The following ReadMe provides information in relation to the creation of a basic full stack web application about various software and coding languages available to use in the current century. The website was created solely to improve the skills in accordance to the programming languages learnt so far (focusing on Ruby on Rails). Due to this, a full website has not been created but the focus has been more on practising to strengthen parts of coding that I find less comfortable.

### Languages used
* Ruby (on Rails)
* Javascript
* CSS / SCSS
* HTML Markup 

### How to download
1. Search for Adnaan-m in GitHub. [Click Here](https://github.com/Adnaan-m/rails_mini_project_hw) for the link.
2. Search for the rails _ mini _ project _ hw repository.
3. Download the files displayed.

### Challenges
* As I focused on certain features of Ruby on Rails from which i was not too comfortable with, it took a while to grasp the knowledge on how to overcome this. My main focus was focusing on th use of the correct filepaths in order to get the correct result or piece of data that was required. I did this by using various IF statements within the code as well as getting familiar with the 'rake routes' functionality on the console log. The following code displays working code that I implemented in an if statement to ensure that only the user who created the field for technologies could amend/delete it and the rest of the audience could only view the information.

```rb
<% if user_signed_in? && tech.user_id == current_user.id %>
        <td><%= link_to 'Edit', edit_technology_path(tech) , class: 'btn btn-info'%></td>
        <td><%= link_to 'Destroy', tech, method: :delete, data: { confirm: 'Are you sure?' } , class: 'btn btn-info'%></td>
      </tr>
      <% end %>
``` 
### Learning points
* The Rake Routes function is awesome! MUCH better than guessing the file path initiation.

>**Created by: Adnaan Mamaniat!**
