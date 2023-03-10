# KOSTIANTYN CHEREDNIKOV
![my-photo] (/images/cv_image.jpeg)
### Front-End Developer
***
## PERSONAL INFORMATION
**Address:** 21029 Vinnitsa
**Email:** worldairsport@gmail.com
**Phone number:** +38 097 469 27 27
***
## ABOUT ME
I really like programming.
I studied HTML and CSS on my own and then took the Front-End Developer course at Beetroot Academy.
I want to continue my in-depth study of JavaScript and gain hands-on experience working under experienced developers as mentors. 
This will help me achieve my goal: - To start my career as a junior Front-End developer and grow in that direction to reach a Seniors position at one of the top companies in the world, such as `<EPAM>`.
I have a great sense of purpose, desire to gain new knowledge and experience in development. 
Good analytical skills, easy to learn and absorb new information. 
Well-developed organizational skills.
I have extensive experience of working in a team.
I am able to make quick decisions in any situation and take responsibility for decisions.
I am able to clearly articulate my point of view.
Listen to the opinion of others.
Adequately perceive criticism and be able to work on mistakes. 
Can manage time effectively.
***
## TECH SKILLS
* GIT
* BEM
* CSS3
* SASS
* HTML5
* React
* Figma
* jQuery
* Gatsby
* Jekyll
* Strapi
* Flexbox
* Next.js
* Gulp.js
* Node.js
* Bootstrap
* XML (AJAX)
* JavaScript
* CSS animation
* Visual Studio
* Docker desktop
* Web-development
* Adaptive layout
* СSS Grid Layout
***
## CODE

*Example 1*

```
.major {
    padding-top: 150px;
    padding-bottom: 145px;
    position: relative;
    &__content {
        max-width: 520px;
        width: 100%;
    }
    &__title {
        font-family: $primaryFont;
        font-weight: 400;
        font-size: 44px;
        line-height: 52px;
        color: $fontPrimaryColor;
        margin: 0 0 20px 0;
    }
    &__text {
        font-family: $primaryFont;
        @include font-style-text;
        color: $fontPrimaryColor;
    }
    @media (max-width: 1280px) and (min-width: 769px) {
        padding-top: 120px;
        padding-bottom: 100px;
    }
    @media (max-width: 768px) {
        padding: 50px 30px 45px;
        &__content {
            max-width: 300px;
            margin: 0 auto;
        }
        &__title {
            font-size: 28px;
            line-height: 32px;
        }
        &__text { 
            font-size: 16px;
            line-height: 24px;
        }
    }
}
```

*Example 2*

```
import Link from "next/link";
import { useRouter } from "next/router";
import BlogList from "./../../../alpina-ui/src/components/Blog/BlogList";

const BlogPage = (props) => {
	const router = useRouter()
	const serviceData = props.data.data;

	return <div>
		{serviceData.map(({ id, attributes }) => (
			<Link key={id} href={'/blog/' + attributes.slug}>
				<BlogList image={attributes.image.data[0].attributes.url} 
									title={attributes.title} 
									description={attributes.description} 
									authorName={attributes.authors.data[0].attributes.name}
									date={attributes.date}
									tags={attributes.tags.data}
				/>
			</Link>
		))}
	</div>
}
export default BlogPage;
```

*Example 3*

```
import BlogTags from "./BlogTags";

const BlogList = (props) => (
	<div className="container">
		<article className="blog-list__item">
			<img src={props.image} alt={props.title}/>
			<div className="blog-list__author">
				<div className="author-name">
					{props.authorName}
				</div>
				<div className="author-date">
					{props.date}
				</div>
						{props.authorName}
					</div>
					<div className="blog-list__title">
						{props.title}
						<svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M1 11L11 1M11 1H1M11 1V11" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
						</svg>
					</div>
					<div className="blog-list__description" style={{ width: '348px', maxWidth: '100%' }}>
						{props.description}
					</div>
				<div className="blog-list__tags">
					<BlogCard/>
				</div>
		</article>
</div>
)
export default BlogList;
```
***
## PROJECTS
[Cards]: https://kostiantyn-cherednikov.netlify.app/cards/index.html
[Shopping_List]: https://kostiantyn-cherednikov.netlify.app/lesson_7/index.html
[my-root-master_backend]: https://github.com/Wokinderech69/my-root-master_backend.git
[my-root-master_frontend]: https://github.com/Wokinderech69/my-root-master_frontend.git
[First_website_with_HTML_and_CSS]: https://kostiantyn-cherednikov.netlify.app/lesson_13/index.html
***
## EDUCATION AND QUALIFICATION
* Specialist Engineer in electronics and telecommunications
	Kharkiv Air Force University, Kharkiv
* Front-End Development 
	Online courses in Beetroot Academy
***
## English
B1 - Pre-Intermediate