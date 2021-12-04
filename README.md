# must install this version.....new version can not found nodule
.npm install swiper@6.8.4
import { Swiper, SwiperSlide } from "swiper/react";

import "swiper/swiper-bundle.min.css";

import "swiper/swiper.min.css";

import "swiper/components/effect-coverflow/effect-coverflow.min.css";

import "swiper/components/navigation/navigation.min.css";

import "swiper/components/pagination/pagination.min.css";

import "./Carous.css";

import SwiperCore, { EffectCoverflow, Navigation, Pagination } from "swiper";

SwiperCore.use([EffectCoverflow, Navigation, Pagination]);
