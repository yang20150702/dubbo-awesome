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
# Warmup Iteration   1: 4.388 ops/ms
# Warmup Iteration   2: 12.126 ops/ms
# Warmup Iteration   3: 12.166 ops/ms
Iteration   1: 12.570 ops/ms
Iteration   2: 12.597 ops/ms
Iteration   3: 12.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.615 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (12.570, 12.615, 12.677), stdev = 0.056
  CI (99.9%): [11.594, 13.635] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ops/ms
# Warmup Iteration   2: 13.097 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 13.110 ops/ms
Iteration   2: 12.891 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.022 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (12.891, 13.022, 13.110), stdev = 0.116
  CI (99.9%): [10.911, 15.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.853 ops/ms
# Warmup Iteration   2: 12.490 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.877 ops/ms
Iteration   2: 12.963 ops/ms
Iteration   3: 12.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.910 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (12.877, 12.910, 12.963), stdev = 0.046
  CI (99.9%): [12.072, 13.749] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.666 ±(99.9%) 0.265 ops/ms [Average]
  (min, avg, max) = (10.651, 10.666, 10.680), stdev = 0.015
  CI (99.9%): [10.401, 10.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.003 ms/op
Iteration   3: 2.511 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.511, 2.520, 2.538), stdev = 0.015
  CI (99.9%): [2.238, 2.801] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.003 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (2.447, 2.452, 2.457), stdev = 0.005
  CI (99.9%): [2.356, 2.547] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.444, 2.454, 2.462), stdev = 0.010
  CI (99.9%): [2.281, 2.628] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.004 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.976, 2.986, 2.996), stdev = 0.010
  CI (99.9%): [2.802, 3.170] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  10.875 ms/op
                 createUser·p0.9999: 14.115 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.408 ms/op
                 createUser·p0.9999: 12.215 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 10.666 ms/op
                 createUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381491
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 185157 
    [ 2.500,  3.750) = 192247 
    [ 3.750,  5.000) = 3209 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.848 ms/op
     p(99.9900) =     13.482 ms/op
     p(99.9990) =     14.555 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.403 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  8.100 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.775 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390262
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 194732 
    [ 2.500,  3.750) = 192549 
    [ 3.750,  5.000) = 2170 
    [ 5.000,  6.250) = 299 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.350 ms/op
     p(99.9900) =     13.090 ms/op
     p(99.9990) =     13.717 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  7.460 ms/op
                 getUser·p0.9999: 15.588 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  5.530 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.276 ms/op
                 getUser·p0.9999: 10.733 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387363
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192593 
    [ 2.500,  3.750) = 190373 
    [ 3.750,  5.000) = 3465 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      6.924 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     16.512 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 3.050 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.536 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.655 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.917 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 10.901 ms/op
                 listUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318291
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 93351 
    [ 2.500,  3.750) = 185025 
    [ 3.750,  5.000) = 32138 
    [ 5.000,  6.250) = 6412 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.269 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     11.692 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.615 ± 1.021  ops/ms
ClientPb.existUser                       thrpt       3  13.022 ± 2.111  ops/ms
ClientPb.getUser                         thrpt       3  12.910 ± 0.838  ops/ms
ClientPb.listUser                        thrpt       3  10.666 ± 0.265  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.095   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.173   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.184   ms/op
ClientPb.createUser                     sample  381491   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.664           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.848           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.482           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.811           ms/op
ClientPb.existUser                      sample  390262   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.779           ms/op
ClientPb.getUser                        sample  387363   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.647           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.924           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.039           ms/op
ClientPb.listUser                       sample  318291   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.655           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.895           ms/op
