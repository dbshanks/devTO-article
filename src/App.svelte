<script>
	import Navigation from './components/Navigation/Navigation.svelte';
	import FormInput from './components/FormInput/FormInput.svelte';
	import Button from './components/Button/Button.svelte';
	import Footer from './components/Footer/Footer.svelte';
</script>

<style lang="scss">
@import './App.scss';
</style>

<div class="main__container">

	<Navigation />

	<form class="form__container">
		<div class="title__container">
		<h1 class="title">Register today <span class="title__ampersand">&</span> </h1>     
		<h1 class="title__secondary">we'll notify you of our launch!</h1>  
		</div> 

		<FormInput 
			inputType={ 'email' } 
			name={ 'email' } 
			classProp={ 'sign__up' } 
			placeholderMsg={ 'Enter your email address....' }
		/>

		<Button 
			btnType={ 'submit' } 
			classType={ 'button' }
			buttonMsg={ 'Submit Email' }
		/>

	</form>

</div>

	<h1 class="large__title">ACME Co.</h1>

<Footer />

