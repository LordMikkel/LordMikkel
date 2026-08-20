```c

#ifndef PROFILE_H
# define PROFILE_H

/* ************************************************************************** */
/*                                    Focus                                   */
/* ************************************************************************** */

typedef struct s_profile
{
	char	*name;
	char	*school;
	char	*languages;
	char	*looking_for;
	char	*focus;
}	t_profile;

static const t_profile	me =
{
	.name = "Mikel Garrido",
	.school = "Computer Science @ 42 Barcelona",
	.languages = "C / C++ / Python / Bash",
	.looking_for = "Internship or junior role",
	.focus = "Cybersecurity research, applied AI and data"
};

/* ************************************************************************** */
/*                                   About                                    */
/* ************************************************************************** */

static const char	*about[] =
{
	"I am a 42 Barcelona student interested in security, AI and data.",
	"I learn by building the thing myself, reading source code,",
	"testing edge cases and writing down what I understood.",
	"My background is practical: C projects, open source, data workflows,",
	"custom AI models and technical workshops.",
	NULL
};


/* ************************************************************************** */
/*                                   Achievements                             */
/* ************************************************************************** */

static const char	*background[] =
{
	"Hackerman achievement at 42: found and responsibly reported",
	"a privilege escalation that gave me access to root.",
	"",
	"Cybersecurity instructor, generative AI developer with LoRA fine-tuning,"
	"encryption data technician, data analyst intern"
	"",
	"Before 42 I got my degree at the University of Barcelona, where I also",
	"taught years later.",
	NULL
};

#endif
```
