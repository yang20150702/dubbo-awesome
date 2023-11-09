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
# Warmup Iteration   1: 4.619 ops/ms
# Warmup Iteration   2: 11.892 ops/ms
# Warmup Iteration   3: 12.398 ops/ms
Iteration   1: 12.436 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.567 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (12.436, 12.567, 12.643), stdev = 0.115
  CI (99.9%): [10.478, 14.656] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 12.871 ops/ms
# Warmup Iteration   3: 12.965 ops/ms
Iteration   1: 13.110 ops/ms
Iteration   2: 13.045 ops/ms
Iteration   3: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.012 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (12.881, 13.012, 13.110), stdev = 0.118
  CI (99.9%): [10.860, 15.164] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.543 ops/ms
# Warmup Iteration   2: 12.281 ops/ms
# Warmup Iteration   3: 12.522 ops/ms
Iteration   1: 12.712 ops/ms
Iteration   2: 12.716 ops/ms
Iteration   3: 12.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.723 ±(99.9%) 0.264 ops/ms [Average]
  (min, avg, max) = (12.712, 12.723, 12.739), stdev = 0.014
  CI (99.9%): [12.459, 12.987] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.580 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (10.558, 10.580, 10.615), stdev = 0.030
  CI (99.9%): [10.023, 11.136] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.506, 2.535, 2.568), stdev = 0.031
  CI (99.9%): [1.966, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.505 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.496, 2.505, 2.518), stdev = 0.011
  CI (99.9%): [2.297, 2.713] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.003 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.523 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.506, 2.523, 2.541), stdev = 0.018
  CI (99.9%): [2.200, 2.845] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.005 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.013, 3.032, 3.043), stdev = 0.017
  CI (99.9%): [2.726, 3.338] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.205 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  10.481 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.082 ms/op
                 createUser·p0.999:  8.457 ms/op
                 createUser·p0.9999: 9.680 ms/op
                 createUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378534
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 181964 
    [ 2.500,  3.750) = 192008 
    [ 3.750,  5.000) = 3492 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.895 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     13.881 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  7.185 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 12.182 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  8.088 ms/op
                 existUser·p0.9999: 11.747 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386715
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 187644 
    [ 2.500,  3.750) = 195019 
    [ 3.750,  5.000) = 3182 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      7.441 ms/op
     p(99.9900) =     13.670 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  11.734 ms/op
                 getUser·p0.9999: 13.717 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.387 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  9.905 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  8.285 ms/op
                 getUser·p0.9999: 11.556 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381223
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 187219 
    [ 2.500,  3.750) = 187745 
    [ 3.750,  5.000) = 4656 
    [ 5.000,  6.250) = 1088 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.007 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.089 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  9.520 ms/op
                 listUser·p0.9999: 10.840 ms/op
                 listUser·p1.00:   11.092 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.436 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.502 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 11.034 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312902
  mean =      3.065 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 83495 
    [ 2.500,  3.750) = 185863 
    [ 3.750,  5.000) = 35181 
    [ 5.000,  6.250) = 6888 
    [ 6.250,  7.500) = 654 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     12.140 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.567 ± 2.089  ops/ms
ClientPb.existUser                       thrpt       3  13.012 ± 2.152  ops/ms
ClientPb.getUser                         thrpt       3  12.723 ± 0.264  ops/ms
ClientPb.listUser                        thrpt       3  10.580 ± 0.556  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.569   ms/op
ClientPb.existUser                        avgt       3   2.505 ± 0.208   ms/op
ClientPb.getUser                          avgt       3   2.523 ± 0.323   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.306   ms/op
ClientPb.createUser                     sample  378534   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.736           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.074           ms/op
ClientPb.existUser                      sample  386715   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.441           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.670           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.400           ms/op
ClientPb.getUser                        sample  381223   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.546           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  312902   3.065 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.502           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
