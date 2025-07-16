**Before code**
<!-- <div class="pricing">
  <div class="card">
    <h2>Basic</h2>
    <p>$10</p>
    <ul>
      <li>1 User</li>
      <li>Email Support</li>
    </ul>
    <button>Subscribe</button>
  </div>
  <div class="card">
    <h2>Pro</h2>
    <p>20</p>
    <ul>
      <li>5 Users</li>
      <li>Priority Support</li>
    </ul>
    <button>Subscribe</button>
  </div>
</div>
<style>
.pricing {
  display: block;
}
.card {
  width: 100px;
  margin: auto;
}
</style>
<script>
document.querySelector("button").addEventListener("click", () => {
  alert("Subscribed!");
});
</script> -->

**AI prompt used**
- This pricing card component has layout issues and unresponsive buttons. Help me fix the bugs, refactor it into a reusable Card(title, price, features) component, and ensure it's responsive.

**After Code**

<!-- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pricing Cards</title>
  <style>
    .pricing {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      padding: 2rem;
    }

    .card {
      flex: 1 1 250px;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 1.5rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    .card h2 {
      margin-bottom: 0.5rem;
    }

    .card p {
      font-size: 1.5rem;
      margin: 0.5rem 0;
    }

    .card ul {
      list-style: none;
      padding: 0;
      margin: 1rem 0;
    }

    .card ul li {
      margin: 0.3rem 0;
    }

    .card button {
      padding: 0.5rem 1rem;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .card button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <div class="pricing">
    <div class="card">
      <h2>Basic</h2>
      <p>$10</p>
      <ul>
        <li>1 User</li>
        <li>Email Support</li>
      </ul>
      <button onclick="subscribe('Basic')">Subscribe</button>
    </div>

    <div class="card">
      <h2>Pro</h2>
      <p>$20</p>
      <ul>
        <li>5 Users</li>
        <li>Priority Support</li>
      </ul>
      <button onclick="subscribe('Pro')">Subscribe</button>
    </div>
  </div>

  <script>
    function subscribe(plan) {
      alert(`You subscribed to the ${plan} plan!`);
    }
  </script>
</body>
</html>
 -->


