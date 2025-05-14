<script>
    let {children} = $props()
    import './styles.css'

</script>

<nav>
    <a href="/">Home</a>
    <a href="/users">Users</a>
    <a href="/contacts">Contacts</a>
</nav>
<div class="container">
{@render children()}
</div>