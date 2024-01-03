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
# Warmup Iteration   1: 5.075 ops/ms
# Warmup Iteration   2: 12.027 ops/ms
# Warmup Iteration   3: 12.323 ops/ms
Iteration   1: 12.379 ops/ms
Iteration   2: 12.473 ops/ms
Iteration   3: 12.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.476 ±(99.9%) 1.789 ops/ms [Average]
  (min, avg, max) = (12.379, 12.476, 12.575), stdev = 0.098
  CI (99.9%): [10.686, 14.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ops/ms
# Warmup Iteration   2: 13.148 ops/ms
# Warmup Iteration   3: 12.958 ops/ms
Iteration   1: 13.082 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.992 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (12.796, 12.992, 13.098), stdev = 0.170
  CI (99.9%): [9.887, 16.097] (assumes normal distribution)


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
# Warmup Iteration   1: 7.796 ops/ms
# Warmup Iteration   2: 12.176 ops/ms
# Warmup Iteration   3: 12.861 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 13.014 ops/ms
Iteration   3: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.934 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (12.770, 12.934, 13.017), stdev = 0.142
  CI (99.9%): [10.347, 15.520] (assumes normal distribution)


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
# Warmup Iteration   1: 6.552 ops/ms
# Warmup Iteration   2: 10.604 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.750 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (10.725, 10.750, 10.767), stdev = 0.021
  CI (99.9%): [10.358, 11.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.560 ±(99.9%) 0.004 ms/op
Iteration   2: 2.614 ±(99.9%) 0.004 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (2.559, 2.577, 2.614), stdev = 0.031
  CI (99.9%): [2.007, 3.148] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.756 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.449, 2.466, 2.478), stdev = 0.015
  CI (99.9%): [2.198, 2.734] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.496, 2.514, 2.534), stdev = 0.019
  CI (99.9%): [2.161, 2.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.512 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.027, 3.044, 3.060), stdev = 0.016
  CI (99.9%): [2.745, 3.344] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.814 ms/op
                 createUser·p0.999:  10.830 ms/op
                 createUser·p0.9999: 13.786 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  5.436 ms/op
                 createUser·p0.9999: 11.928 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.929 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376222
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 180124 
    [ 2.500,  3.750) = 191790 
    [ 3.750,  5.000) = 3470 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     15.412 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.520 ms/op
                 existUser·p0.999:  5.317 ms/op
                 existUser·p0.9999: 13.718 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.694 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.872 ms/op
                 existUser·p0.999:  7.906 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379736
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 185519 
    [ 2.500,  3.750) = 190662 
    [ 3.750,  5.000) = 2804 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 140 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      5.731 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  11.618 ms/op
                 getUser·p0.9999: 14.045 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  9.777 ms/op
                 getUser·p0.9999: 12.954 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  6.569 ms/op
                 getUser·p0.9999: 11.569 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384531
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 192173 
    [ 2.500,  3.750) = 187853 
    [ 3.750,  5.000) = 3593 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      8.413 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.707 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.009 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.737 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.564 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.139 ms/op
                 listUser·p0.9999: 11.553 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320176
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 94867 
    [ 2.500,  3.750) = 186141 
    [ 3.750,  5.000) = 31839 
    [ 5.000,  6.250) = 6064 
    [ 6.250,  7.500) = 482 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     11.155 ms/op
     p(99.9990) =     12.023 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.476 ± 1.789  ops/ms
ClientPb.existUser                       thrpt       3  12.992 ± 3.105  ops/ms
ClientPb.getUser                         thrpt       3  12.934 ± 2.587  ops/ms
ClientPb.listUser                        thrpt       3  10.750 ± 0.391  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.571   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.353   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.299   ms/op
ClientPb.createUser                     sample  376222   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.908           ms/op
ClientPb.existUser                      sample  379736   2.526 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  384531   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.413           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.188           ms/op
ClientPb.listUser                       sample  320176   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.155           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
