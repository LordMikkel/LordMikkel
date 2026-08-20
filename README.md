```c
/* ************************************************************************** */
/*                                                                            */
/*                                                                            */
/*   profile.h                                                                */
/*                                                                            */
/*   By: Mikel Garrido <@LordMikkel>                                          */
/*                                                                            */
/*   Created: 2026/08/20 by migarrid                                          */
/*                                                                            */
/* ************************************************************************** */

#ifndef PROFILE_H
# define PROFILE_H

/*
** RESUME
*/

typedef enum e_focus
{
	SECURITY_RESEARCH,
	APPLIED_AI,
	DATA_ENGINEERING,
}	t_focus;

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
	.languages = "C / C++ / Python",
	.looking_for = "Internship or junior role",
	.focus = "Cybersecurity research, applied AI and data"
};

/*
** SHORT BIO
*/
static const char	*about[] =
{
	"I am a 42 Barcelona student interested in security, AI and data.",
	"I learn by building the thing myself, reading source code,",
	"testing edge cases and writing down what I understood.",
	"My background is practical: C projects, open source, data workflows,",
	"custom AI models and technical workshops.",
	NULL
};


/*
** ARCHIVEMENTS
**
*/
static const char	*background[] =
{
	"Hackerman achievement at 42: found and responsibly reported",
	"a privilege escalation that exposed access to /etc/shadow.",
	"",
	"Cybersecurity instructor (CTF workshops), generative AI developer",
	"with LoRA fine-tuning, data technician, data analyst intern and",
	"web systems technician.",
	"",
	"Before 42 I studied at the University of Barcelona, where I also",
	"taught and later helped coordinate a project with more than 70 people.",
	NULL
};


static const char	*languages[] =
{
	"Spanish: native",
	"English: professional",
	"German: elementary",
	NULL
};


#endif
```
