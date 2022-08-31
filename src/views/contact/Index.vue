<template>
    <div class="post-index">
        <!-- header -->
        <Header />
        <!-- end header -->

        <!-- main content -->
        <header class="pt-5 border-bottom bg-light">
            <div class="container pt-md-1 pb-md-1">
                <h1 class="bd-title mt-4 font-weight-bold"><i class="fa fa-phone" aria-hidden="true"></i> KONTAK</h1>
                <p class="bd-lead">Kontak SMK Antartika 1 Sidoarjo.</p>
            </div>
        </header>

        <!-- breadcrumb -->
        <nav aria-label="breadcrumb">
            <ol class="breadcrumb">
                <li class="breadcrumb-item">
                    <router-link :to="{ name: 'home' }" class="text-decoration-none"><i class="fa fa-home"></i> Home
                    </router-link>
                </li>
                <li class="breadcrumb-item">
                    <router-link :to="{ name: 'contact' }" class="text-decoration-none"><i class="fa fa-phone"></i>
                        Kontak</router-link>
                </li>
            </ol>
        </nav>
        <!-- end breadcrumb -->

        <div class="container-fluid mt-5 mb-5">

            <div class="row">
                <div class="col-md-7">
                    <div class="card border-0 shadow-sm rounded">
                        <div class="card-body">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3956.2880299303506!2d112.72876821400835!3d-7.433345975293192!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd7e6a663d94b21%3A0x3a57baa5fb4760ce!2sSMK%20Antartika%201%20Sidoarjo!5e0!3m2!1sid!2sid!4v1659931895042!5m2!1sid!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                        </div>
                    </div>
                </div>
                <div class="col-md-5">
                    <div class="card border-0 shadow-sm rounded">
                        <div class="card-body">
                            <h3>KONTAK KAMI</h3>
                            <hr>
                            <p>
                                <i class="fa fa-map-marker" aria-hidden="true"></i> Jl.Siwalanpanji, Kec. Buduran Sidoarjo, Indonesia
                            </p>
                            <p>
                                <i class="fas fa-phone"></i> +6231-8962851
                            </p>
                            <p>
                                <i class="fas fa-envelope"></i> smks.antartika1.sda@gmail.com
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- main content -->

        <!-- footer -->
        <Footer />
        <!-- end footer -->
    </div>
</template>

<script>
    //import component
    import Header from "@/components/Header";
    import Footer from "@/components/Footer";


    export default {
        name: 'ContactComponent',
        components: {
            Header,
            Footer
        }
    }
</script>