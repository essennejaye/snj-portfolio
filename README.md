# Portfolio Page for Satalia Jefferson

## Introduction

> This page presents the repository and published sites for the web development projects of Satalia Jefferson.
  Currently the languages showcased are HTML5 and CSS3.

## Code Samples

>HTML of contact me section of page

     <!-- contact info and links to linkedin and github -->
    <section class="section-container" id="contact-me">
        <h2 class="section-title">Contact<br> Me</h2>
        <div class="contact-container">
            <div class="flex-item e-mail">
                <a href="mailto:sjeffers02@gmail.com/" target="_blank">E: sjeffers02@gmail.com</a>
            </div>
            <div class="flex-item phone-number">
                <p>
                    P: 443-985-6501
                </p>
            </div>
            <div class="flex-item linkedin-link">
                <a href="http://www.linkedin.com/in/satalia-n-jefferson-87037a114/" target="_blank"><img
                        src="./assets/images/linkedin_icon.png" alt="linkedin icon" /></a>
            </div>
            <div class="flex-item github-link">
                <a href="https://github.com/essennejaye/" target="_blank"><img src="./assets/images/github_icon.png"
                        alt="github logo" /></a>
            </div>
        </div>
    </section>
>CSS code for media query

          @media screen and (max-width: 768px) {
            header {
              position: relative;
            }
            .profile-pic,
            .quote {
              display: flex;
              justify-content: center;
            }
            .contact-container {
              height: 150px;
            }
            .contact-container img {
              height: 3vh;
              object-fit: contain;
              width: 100%;
            }
            .e-mail,
            .phone-number {
              font-size: 22px;
            }
          }
 
## Screenshots
![](/assets/images/portfolio_screenshot(1).png)
![](/assets/images/protfolio_screenshot(2).png)
![](/assets/images/protfolio_screenshot(3).png)
