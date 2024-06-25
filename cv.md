![photo](./avatarka.jpg "avatar")

# Siarhei Douhi

## Contacts

- Phone: +375295940687
- Email: [serrik22@mail.ru](https://serrik22@mail.ru "email")
- GitHub: [Siarhei Douhi](https://github.com/Siarhei-Douhi "GitHub")
- Discord: siarhei_douhi

## About me

I want to be a computer programmer.

## Skills

- HTML
- Css
- JavaScript
- TypeScript
- React
- Git
- GitHub
- Figma

## Code Examples

```TypeScript
export const Time = () => {
  const [time, setTime] = useState(new Date().toLocaleTimeString());
  const { isDark } = useContext(Context);

  useEffect(() => {
    const timerId = setInterval(() => {
      setTime(new Date().toLocaleTimeString());
    }, 1000);

    return () => {
      clearInterval(timerId);
    };
  }, []);

  return (
    <div className={`${style.clock} ${isDark ? style.clockDark : ""}`}>
      {time}
    </div>
  );
};
```

## Experience

_JavaScript_ - teamwork on a project [Trello](https://github.com/Siarhei-Douhi/Trello "project Trello")  
_React + TypeScript_ - a project [how-strong-are-you](https://github.com/Siarhei-Douhi/how-strong-are-you "my React project"). It is my final work in **TeachMeSkills**

## Education :book:

**TeachMeSkills** - "Front End Developer" (February 28, 2022 - November 16, 2022)

## Languages

- English (A2)
