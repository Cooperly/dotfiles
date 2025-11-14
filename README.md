# void's Dotfiles

A non-standard workflow, unappealing visuals compared to every other configuration, and lackluster immediate functionality.

But it works pretty damn good.

> [!NOTE]
> You will need to modify the Niri config to your system if you plan to use my Niri config, please refer to the [Niri Documentation](https://yalter.github.io/niri/) for assistance.
>
> In addition, **there will be very little support granted for this repository**.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1e2ae3a1-2e48-4f4f-8379-cd191acc4250" />

## Prerequisites
- Desktop Environment
  - [Niri](https://github.com/YaLTeR/niri)
  - [NiriSwitcher](https://github.com/isaksamsten/niriswitcher)
  - [WayBar](https://github.com/Alexays/Waybar)
  - [Mako](https://github.com/emersion/mako)
- Terminal
  - [Alacritty](https://github.com/alacritty/alacritty) 
  - [Fish](https://github.com/fish-shell/fish-shell)
  - [Starship](https://github.com/starship/starship)
  - [FastFetch](https://github.com/fastfetch-cli/fastfetch)

## Installation
- Install all Prerequisites using your package manager of choice.
- Backup every folder and file in `~/.config/` that will be modified.
- Clone this repository locally
- Merge the `.config` from this repository to `~/.config/`

## Thoughts
### Themeing

I was heavily inspired by Zorin OS Purple Dark when making my color scheme, however made some changes to the primary text color to make it Protobit's brand color (I really like it if you can't tell) and just made every color lighter overall. I call it ProtoPurple.

Rubik as a font looks aesthetically pleasing, I would love a monospaced version for my clock though.

I also attempt to theme my applications to this style whenever possible, and I rip the client-side decorations (titlebar, close/minimize/maximize buttons) so I don't have to deal with GTK and QT apps looking different, not like I used them frequently anyway.

### Niri

Niri is a tiling window manager with unlimited horizontal space, this is untraditional compared to any other DE/WM.

It's really customizable and also really lightweight.

What this allows me to do is make all my windows maximized by default, and I essentially have unlimited horizontal and vertical space to work with for all my applications.

Niri's workspaces (vertical space) are used to sort applications by type, and I can use horizontal space to switch to various applications which are maximized by default, which is nice compared to having to deal with small windows when realistically most of my time is going to be spent with applications maximized. 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8bc66ec2-47f3-4aaa-aeb3-9efdfe1e0c6d" />

### NiriSwitcher

It allows me to Alt+Tab which Niri doesn't have functionality for by default, not too special.

### Waybar

Was partially inspired by [GNOME](https://gitlab.gnome.org/GNOME/gnome-desktop) as I like how it looks, however GNOME itself sucked to use, and I don't personally really like how GTK looks.

I have my current active application information on the left to replace the fact that I've purposfully removed CSD from all applications, an update checker besides my time (as I look at it extremely frequently), a friend's time, and my system vitals on the right. (CPU, Memory)

<img width="1920" height="28" alt="image" src="https://github.com/user-attachments/assets/ea515ef7-8ed8-42af-a02b-a72c1842f8d4" />

### Mako

I was considering just not having a notification daemon, as I've always personally disliked notifications. But some applications hang otherwise, and it lets me glance at information when it comes through.

Mako kind of works, it's really barebones though.

<img width="306" height="50" alt="image" src="https://github.com/user-attachments/assets/8a95f91c-b129-41aa-aa2f-89a2c7ba4aff" />

### Alacritty

Great barebones terminal emulator to theme, and isn't loaded with stuff I may or may not need like Konsole.

<img width="1920" height="1056" alt="image" src="https://github.com/user-attachments/assets/01ef5bd9-8dad-45e9-b0f2-c6b7407a4500" />

### Fish

Better autocorrects are nice, and the fish syntax is a lot easier to work with for scripting.

### Starship

I kind of liked modified shell prompts so I finally decided to have a go at it, think it turned out pretty well.

Unlike a lot of pre-existing configurations, I chose to not bombard myself with information I don't generally need, it's kind of overwhelming and also looks weird empty if that information isn't applicable. (such as code language)

<img width="234" height="92" alt="image" src="https://github.com/user-attachments/assets/ad91a760-f1fa-4ead-8e75-5174323fdd8a" />


### Fastfetch

Nothing is complete without this.

<img width="655" height="184" alt="image" src="https://github.com/user-attachments/assets/7ce84e77-1549-4cf3-a4cc-604dc9012d95" />




