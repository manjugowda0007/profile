import ProfileCard from "./components/ProfileCard";

function App() {
  return (
    <div style={{
      minHeight: "100vh",
      display: "flex",
      justifyContent: "center",
      alignItems: "center",
      background: "#020617"
    }}>
      <ProfileCard
  name="Manju Gowda"
  
  handle="_manju.gowda_"
  status="Online"
  avatarUrl="/pto.png"
  miniAvatarUrl="/pto.png"
  onContactClick={() =>
    window.open("https://www.instagram.com/_manju.gowda_/", "_blank")
  }
/>

    </div>
  );
}

export default App;
