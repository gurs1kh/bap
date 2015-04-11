# Bap

Beatmaking and sequence composition toolkit, using Javascript and Web Audio

Made by [Adam Renklint](http://adamrenklint.com)

**BEWARE, THIS IS ALPHA SOFTWARE. NOT READY YET.**

[![npm](https://img.shields.io/npm/v/bap.svg?style=flat-square)](https://www.npmjs.com/package/bap) [![npm](https://img.shields.io/npm/dm/bap.svg?style=flat-square)](https://www.npmjs.com/package/bap) [![Travis branch](https://img.shields.io/travis/adamrenklint/bap/dev.svg?style=flat-square)](https://travis-ci.org/adamrenklint/bap) [![Code Climate](https://img.shields.io/codeclimate/github/adamrenklint/bap.svg?style=flat-square)](https://codeclimate.com/github/adamrenklint/bap) [![Code Climate](https://img.shields.io/codeclimate/coverage/github/adamrenklint/bap.svg?style=flat-square)](https://codeclimate.com/github/adamrenklint/bap) [![David dependencies](https://img.shields.io/david/adamrenklint/bap.svg?style=flat-square)](https://david-dm.org/adamrenklint/bap) [![David devDependencies](https://img.shields.io/david/dev/adamrenklint/bap.svg?style=flat-square)](https://david-dm.org/adamrenklint/bap#info=devDependencies) [![GitHub stars](https://img.shields.io/github/stars/adamrenklint/bap.svg?style=flat-square)](https://github.com/adamrenklint/bap) [![GitHub forks](https://img.shields.io/github/forks/adamrenklint/bap.svg?style=flat-square)](https://github.com/adamrenklint/bap)

## Summary

> Public demos, examples

## Install

## Usage

### Example: metronome

## API

### bap

- ```bap.kit(params)``` returns a new [kit](#kit)
- ```bap.slot()``` returns a new [slot](#slot)
- ```bap.layer()``` returns a new [layer](#layer)
- ```bap.pattern()``` returns a new [pattern](#pattern)
- ```bap.sequence()``` returns a new [sequence](#sequence)
- ```bap.channel()``` returns a new [channel](#channel)
- ```bap.note()``` returns a new [note](#note)

### kit

- ```kit.slot()``` returns blank [slot](#slot) assigned to next index
- ```kit.slot(index)``` returns existing or blank slot with index
- ```kit.slot(index, slot)``` set slot instance at index
- ```kit.trigger(note)``` trigger note immediately with required note
- ```kit.triggerAt(position, note)``` trigger note at position with required note

### slot

- ```slot.layer()``` returns a blank [layer](#layer) assigned to next index
- ```slot.layer(source)``` returns a new layer containing [source](#source), assigned to next index
- ```slot.layer(sampleSrc)``` returns a new layer containing [sample](#sample) with src, assigned to next index
- ```slot.layer(index)``` returns existing or blank layer with index
- ```slot.layer(index, layer)``` set layer instance at index
- ```slot.layer(index, source)``` creates a new layer containing [source](#source), assigns to index
- ```slot.layer(index, sampleSrc)``` creates a new layer containing [sample](#sample), assigns to index
- ```slot.schedule(event)```
- ```slot.trigger(note)``` trigger slot immediately with optional note
- ```slot.triggerAt(position, note)``` trigger slot at position with optional note

### layer

- ```layer.set(source)``` define layer [source](#source)

### source

- sample, oscillator

### sample

### pattern

- is [playable](#playable) and automatically looped

### sequence

### channel

### note

### playable

## Develop

## Contribute

## License
