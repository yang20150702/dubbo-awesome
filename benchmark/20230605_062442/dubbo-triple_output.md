# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.046 ops/ms
# Warmup Iteration   2: 5.828 ops/ms
# Warmup Iteration   3: 8.789 ops/ms
Iteration   1: 8.908 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 9.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.335 ±(99.9%) 7.469 ops/ms [Average]
  (min, avg, max) = (8.908, 9.335, 9.724), stdev = 0.409
  CI (99.9%): [1.867, 16.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 8.889 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 9.750 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.910 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (9.750, 9.910, 9.995), stdev = 0.138
  CI (99.9%): [7.387, 12.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 9.547 ops/ms
Iteration   1: 9.325 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.490 ±(99.9%) 4.493 ops/ms [Average]
  (min, avg, max) = (9.325, 9.490, 9.774), stdev = 0.246
  CI (99.9%): [4.997, 13.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.901 ops/ms
# Warmup Iteration   2: 7.352 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.265 ±(99.9%) 2.792 ops/ms [Average]
  (min, avg, max) = (8.136, 8.265, 8.434), stdev = 0.153
  CI (99.9%): [5.473, 11.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.562 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.006 ms/op
Iteration   1: 3.379 ±(99.9%) 0.007 ms/op
Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
Iteration   3: 3.219 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 1.557 ms/op [Average]
  (min, avg, max) = (3.219, 3.316, 3.379), stdev = 0.085
  CI (99.9%): [1.759, 4.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.605 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.004 ms/op
Iteration   1: 3.215 ±(99.9%) 0.009 ms/op
Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
Iteration   3: 3.173 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.183 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (3.161, 3.183, 3.215), stdev = 0.028
  CI (99.9%): [2.665, 3.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.285 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.006 ms/op
Iteration   1: 3.399 ±(99.9%) 0.006 ms/op
Iteration   2: 3.302 ±(99.9%) 0.008 ms/op
Iteration   3: 3.303 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.335 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.302, 3.335, 3.399), stdev = 0.056
  CI (99.9%): [2.314, 4.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.570 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.007 ms/op
Iteration   1: 4.041 ±(99.9%) 0.007 ms/op
Iteration   2: 3.941 ±(99.9%) 0.008 ms/op
Iteration   3: 3.865 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.949 ±(99.9%) 1.613 ms/op [Average]
  (min, avg, max) = (3.865, 3.949, 4.041), stdev = 0.088
  CI (99.9%): [2.336, 5.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.072 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  20.318 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  9.595 ms/op
                 createUser·p0.9999: 24.004 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.370 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 33.195 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287068
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12226 
    [ 2.500,  5.000) = 269660 
    [ 5.000,  7.500) = 4272 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     20.265 ms/op
     p(99.9900) =     32.049 ms/op
     p(99.9990) =     33.534 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  11.276 ms/op
                 existUser·p0.9999: 22.225 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.307 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.623 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   3: 3.305 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  17.797 ms/op
                 existUser·p0.9999: 29.961 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292124
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17982 
    [ 2.500,  5.000) = 268850 
    [ 5.000,  7.500) = 4468 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     10.891 ms/op
     p(99.9900) =     26.554 ms/op
     p(99.9990) =     30.820 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.377 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.819 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  15.944 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   2: 3.361 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  17.622 ms/op
                 getUser·p0.9999: 24.738 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.414 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  15.806 ms/op
                 getUser·p0.9999: 22.161 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284442
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1575 
    [ 2.500,  5.000) = 275285 
    [ 5.000,  7.500) = 6472 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     15.980 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.028 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.605 ms/op
                 listUser·p0.999:  18.378 ms/op
                 listUser·p0.9999: 24.605 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.419 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 16.970 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.161 ms/op
                 listUser·p0.999:  14.346 ms/op
                 listUser·p0.9999: 15.681 ms/op
                 listUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244483
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 235722 
    [ 5.000,  7.500) = 6356 
    [ 7.500, 10.000) = 1561 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     24.055 ms/op
     p(99.9990) =     24.922 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.335 ± 7.469  ops/ms
ClientPb.existUser                       thrpt       3   9.910 ± 2.523  ops/ms
ClientPb.getUser                         thrpt       3   9.490 ± 4.493  ops/ms
ClientPb.listUser                        thrpt       3   8.265 ± 2.792  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 1.557   ms/op
ClientPb.existUser                        avgt       3   3.183 ± 0.518   ms/op
ClientPb.getUser                          avgt       3   3.335 ± 1.021   ms/op
ClientPb.listUser                         avgt       3   3.949 ± 1.613   ms/op
ClientPb.createUser                     sample  287068   3.341 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.292           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  292124   3.283 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.891           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.195           ms/op
ClientPb.getUser                        sample  284442   3.372 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.980           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  244483   3.924 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.055           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526           ms/op
