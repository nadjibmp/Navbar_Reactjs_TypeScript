# Navbar_Reactjs_TypeScript
This is an implementation of a navbar using typescript and react js and styledComponent  with tailwinds

you can call the component using this line : 

< Navbar links={[]} logo={logo} /> 

links props accept an array of of object, each object contain the link and it's alias.
logo props accept a full path of the logo in the project .

exemple of link array : 

const NavLinks: Link[] = [
    {
        link: "/",
        alias: "About"
    },
    {
        link: "/",
        alias: "Experience"
    },
    {
        link: "/",
        alias: "Work"
    },
    {
        link: "/",
        alias: "Contact"
    },
];

with type :

export type Link = {
    link: string,
    alias: string
};
