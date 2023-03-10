# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.198 ops/ms
# Warmup Iteration   2: 5.485 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 9.234 ops/ms
Iteration   2: 9.352 ops/ms
Iteration   3: 9.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.391 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (9.234, 9.391, 9.585), stdev = 0.178
  CI (99.9%): [6.134, 12.647] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 9.445 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 10.272 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.022 ±(99.9%) 4.362 ops/ms [Average]
  (min, avg, max) = (9.796, 10.022, 10.272), stdev = 0.239
  CI (99.9%): [5.660, 14.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 8.690 ops/ms
# Warmup Iteration   3: 9.740 ops/ms
Iteration   1: 9.971 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.942 ±(99.9%) 6.389 ops/ms [Average]
  (min, avg, max) = (9.578, 9.942, 10.277), stdev = 0.350
  CI (99.9%): [3.553, 16.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 8.516 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.219 ±(99.9%) 3.291 ops/ms [Average]
  (min, avg, max) = (8.014, 8.219, 8.355), stdev = 0.180
  CI (99.9%): [4.928, 11.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.709 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.004 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
Iteration   3: 3.286 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.365 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (3.286, 3.365, 3.411), stdev = 0.069
  CI (99.9%): [2.114, 4.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.280 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.007 ms/op
Iteration   1: 3.366 ±(99.9%) 0.005 ms/op
Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
Iteration   3: 3.422 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.382 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.357, 3.382, 3.422), stdev = 0.035
  CI (99.9%): [2.746, 4.017] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.401 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.005 ms/op
Iteration   1: 3.496 ±(99.9%) 0.003 ms/op
Iteration   2: 3.363 ±(99.9%) 0.011 ms/op
Iteration   3: 3.402 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.421 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (3.363, 3.421, 3.496), stdev = 0.068
  CI (99.9%): [2.174, 4.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.514 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.008 ms/op
Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
Iteration   2: 4.141 ±(99.9%) 0.006 ms/op
Iteration   3: 3.859 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.991 ±(99.9%) 2.591 ms/op [Average]
  (min, avg, max) = (3.859, 3.991, 4.141), stdev = 0.142
  CI (99.9%): [1.399, 6.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.350 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.412 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  20.819 ms/op
                 createUser·p0.9999: 29.492 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  21.684 ms/op
                 createUser·p0.9999: 26.467 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  16.728 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276304
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11276 
    [ 2.500,  5.000) = 257758 
    [ 5.000,  7.500) = 6278 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.867 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.187 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.288 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.447 ms/op
                 existUser·p0.9999: 24.126 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.176 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 26.726 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 26.949 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296957
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14059 
    [ 2.500,  5.000) = 278628 
    [ 5.000,  7.500) = 3399 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     26.093 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.199 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.011 ms/op
Iteration   1: 3.648 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  20.045 ms/op
                 getUser·p0.9999: 30.226 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  21.853 ms/op
                 getUser·p0.9999: 29.180 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  20.047 ms/op
                 getUser·p0.9999: 24.565 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276076
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8525 
    [ 2.500,  5.000) = 256114 
    [ 5.000,  7.500) = 10168 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     20.051 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     30.482 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.591 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.014 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  20.840 ms/op
                 listUser·p0.9999: 24.994 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.005 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.314 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241695
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 232489 
    [ 5.000,  7.500) = 7240 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     23.614 ms/op
     p(99.9990) =     25.349 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.391 ± 3.256  ops/ms
ClientPb.existUser                       thrpt       3  10.022 ± 4.362  ops/ms
ClientPb.getUser                         thrpt       3   9.942 ± 6.389  ops/ms
ClientPb.listUser                        thrpt       3   8.219 ± 3.291  ops/ms
ClientPb.createUser                       avgt       3   3.365 ± 1.252   ms/op
ClientPb.existUser                        avgt       3   3.382 ± 0.635   ms/op
ClientPb.getUser                          avgt       3   3.421 ± 1.247   ms/op
ClientPb.listUser                         avgt       3   3.991 ± 2.591   ms/op
ClientPb.createUser                     sample  276304   3.475 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.048           ms/op
ClientPb.existUser                      sample  296957   3.231 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.008           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.093           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  276076   3.479 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.013           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.051           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.360           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  241695   3.971 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.187           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.614           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
