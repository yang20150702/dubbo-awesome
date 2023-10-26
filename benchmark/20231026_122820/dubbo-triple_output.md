# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.906 ops/ms
# Warmup Iteration   2: 4.734 ops/ms
# Warmup Iteration   3: 8.483 ops/ms
Iteration   1: 9.016 ops/ms
Iteration   2: 9.098 ops/ms
Iteration   3: 9.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.130 ±(99.9%) 2.424 ops/ms [Average]
  (min, avg, max) = (9.016, 9.130, 9.276), stdev = 0.133
  CI (99.9%): [6.707, 11.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 9.559 ops/ms
Iteration   1: 9.578 ops/ms
Iteration   2: 9.733 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.664 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (9.578, 9.664, 9.733), stdev = 0.079
  CI (99.9%): [8.218, 11.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.179 ops/ms
# Warmup Iteration   2: 8.731 ops/ms
# Warmup Iteration   3: 9.235 ops/ms
Iteration   1: 9.251 ops/ms
Iteration   2: 9.351 ops/ms
Iteration   3: 9.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.230 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (9.089, 9.230, 9.351), stdev = 0.132
  CI (99.9%): [6.820, 11.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.701 ops/ms
# Warmup Iteration   2: 7.154 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 7.746 ops/ms
Iteration   2: 7.915 ops/ms
Iteration   3: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.806 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (7.746, 7.806, 7.915), stdev = 0.094
  CI (99.9%): [6.090, 9.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.423 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.007 ms/op
Iteration   1: 3.475 ±(99.9%) 0.006 ms/op
Iteration   2: 3.526 ±(99.9%) 0.005 ms/op
Iteration   3: 3.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.502 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.475, 3.502, 3.526), stdev = 0.026
  CI (99.9%): [3.034, 3.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.041 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.003 ms/op
Iteration   1: 3.361 ±(99.9%) 0.006 ms/op
Iteration   2: 3.359 ±(99.9%) 0.003 ms/op
Iteration   3: 3.387 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.369 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.359, 3.369, 3.387), stdev = 0.016
  CI (99.9%): [3.084, 3.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.439 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.003 ms/op
Iteration   1: 3.494 ±(99.9%) 0.004 ms/op
Iteration   2: 3.418 ±(99.9%) 0.008 ms/op
Iteration   3: 3.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.457 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.418, 3.457, 3.494), stdev = 0.038
  CI (99.9%): [2.759, 4.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.078 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.006 ms/op
Iteration   1: 4.120 ±(99.9%) 0.009 ms/op
Iteration   2: 4.089 ±(99.9%) 0.006 ms/op
Iteration   3: 4.120 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.110 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (4.089, 4.110, 4.120), stdev = 0.018
  CI (99.9%): [3.785, 4.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.368 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.016 ms/op
Iteration   1: 3.552 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  21.462 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  22.717 ms/op
                 createUser·p0.9999: 27.612 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  24.805 ms/op
                 createUser·p0.9999: 28.343 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273730
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4108 
    [ 2.500,  5.000) = 264139 
    [ 5.000,  7.500) = 4191 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 101 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     21.752 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.660 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  20.063 ms/op
                 existUser·p0.9999: 24.695 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.437 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  22.443 ms/op
                 existUser·p0.9999: 25.877 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  12.351 ms/op
                 existUser·p0.9999: 27.872 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278150
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5676 
    [ 2.500,  5.000) = 266510 
    [ 5.000,  7.500) = 5024 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     28.587 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.750 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.012 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  20.910 ms/op
                 getUser·p0.9999: 26.079 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 3.539 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  23.214 ms/op
                 getUser·p0.9999: 26.696 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  22.273 ms/op
                 getUser·p0.9999: 26.497 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272851
  mean =      3.514 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2754 
    [ 2.500,  5.000) = 264148 
    [ 5.000,  7.500) = 4768 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.576 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.610 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.012 ms/op
Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  20.733 ms/op
                 listUser·p0.9999: 24.153 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 4.202 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 18.492 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.154 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.844 ms/op
                 listUser·p0.9999: 18.458 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230330
  mean =      4.164 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 221194 
    [ 5.000,  7.500) = 7225 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 260 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     22.837 ms/op
     p(99.9990) =     24.733 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.130 ± 2.424  ops/ms
ClientPb.existUser                       thrpt       3   9.664 ± 1.446  ops/ms
ClientPb.getUser                         thrpt       3   9.230 ± 2.411  ops/ms
ClientPb.listUser                        thrpt       3   7.806 ± 1.716  ops/ms
ClientPb.createUser                       avgt       3   3.502 ± 0.468   ms/op
ClientPb.existUser                        avgt       3   3.369 ± 0.285   ms/op
ClientPb.getUser                          avgt       3   3.457 ± 0.698   ms/op
ClientPb.listUser                         avgt       3   4.110 ± 0.324   ms/op
ClientPb.createUser                     sample  273730   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.752           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.622           ms/op
ClientPb.existUser                      sample  278150   3.447 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.575           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  272851   3.514 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.332           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  230330   4.164 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.905           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.837           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
