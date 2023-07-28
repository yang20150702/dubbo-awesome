# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 5.452 ops/ms
# Warmup Iteration   3: 8.616 ops/ms
Iteration   1: 9.087 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 8.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.059 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (8.872, 9.059, 9.217), stdev = 0.174
  CI (99.9%): [5.880, 12.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 9.001 ops/ms
# Warmup Iteration   3: 9.675 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 9.900 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.771 ±(99.9%) 2.139 ops/ms [Average]
  (min, avg, max) = (9.670, 9.771, 9.900), stdev = 0.117
  CI (99.9%): [7.632, 11.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.251 ops/ms
# Warmup Iteration   2: 8.184 ops/ms
# Warmup Iteration   3: 8.577 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.041 ops/ms
Iteration   3: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.185 ±(99.9%) 2.316 ops/ms [Average]
  (min, avg, max) = (9.041, 9.185, 9.279), stdev = 0.127
  CI (99.9%): [6.869, 11.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.802 ±(99.9%) 2.778 ops/ms [Average]
  (min, avg, max) = (7.650, 7.802, 7.954), stdev = 0.152
  CI (99.9%): [5.024, 10.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.750 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.005 ms/op
Iteration   1: 3.443 ±(99.9%) 0.004 ms/op
Iteration   2: 3.440 ±(99.9%) 0.012 ms/op
Iteration   3: 3.438 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (3.438, 3.440, 3.443), stdev = 0.003
  CI (99.9%): [3.393, 3.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.005 ms/op
Iteration   1: 3.326 ±(99.9%) 0.007 ms/op
Iteration   2: 3.305 ±(99.9%) 0.005 ms/op
Iteration   3: 3.334 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.322 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.305, 3.322, 3.334), stdev = 0.015
  CI (99.9%): [3.048, 3.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.738 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.004 ms/op
Iteration   1: 3.400 ±(99.9%) 0.005 ms/op
Iteration   2: 3.416 ±(99.9%) 0.004 ms/op
Iteration   3: 3.432 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.400, 3.416, 3.432), stdev = 0.016
  CI (99.9%): [3.129, 3.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.689 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.005 ms/op
Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
Iteration   2: 4.059 ±(99.9%) 0.008 ms/op
Iteration   3: 3.939 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.017 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.939, 4.017, 4.059), stdev = 0.068
  CI (99.9%): [2.782, 5.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.609 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
Iteration   1: 3.374 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  20.846 ms/op
                 createUser·p0.9999: 24.086 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  11.214 ms/op
                 createUser·p0.9999: 32.113 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   3: 3.537 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282487
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10309 
    [ 2.500,  5.000) = 266108 
    [ 5.000,  7.500) = 5008 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     18.924 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.184 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
Iteration   1: 3.334 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.127 ms/op
                 existUser·p0.999:  18.979 ms/op
                 existUser·p0.9999: 22.080 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.271 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.438 ms/op
                 existUser·p0.9999: 23.895 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.323 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  18.006 ms/op
                 existUser·p0.9999: 32.354 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289909
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9945 
    [ 2.500,  5.000) = 274601 
    [ 5.000,  7.500) = 4370 
    [ 7.500, 10.000) = 625 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.436 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     33.397 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.610 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.012 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  19.387 ms/op
                 getUser·p0.9999: 25.253 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.403 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  21.005 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 28.046 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277623
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5075 
    [ 2.500,  5.000) = 263568 
    [ 5.000,  7.500) = 7866 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     26.606 ms/op
     p(99.9990) =     28.432 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.816 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.014 ms/op
Iteration   1: 4.093 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.298 ms/op
                 listUser·p0.999:  24.576 ms/op
                 listUser·p0.9999: 28.717 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 4.101 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.511 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236670
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 228756 
    [ 5.000,  7.500) = 5687 
    [ 7.500, 10.000) = 1422 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     17.280 ms/op
     p(99.9900) =     26.913 ms/op
     p(99.9990) =     29.428 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.059 ± 3.179  ops/ms
ClientPb.existUser                       thrpt       3   9.771 ± 2.139  ops/ms
ClientPb.getUser                         thrpt       3   9.185 ± 2.316  ops/ms
ClientPb.listUser                        thrpt       3   7.802 ± 2.778  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 0.048   ms/op
ClientPb.existUser                        avgt       3   3.322 ± 0.274   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   4.017 ± 1.236   ms/op
ClientPb.createUser                     sample  282487   3.398 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.764           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.096           ms/op
ClientPb.existUser                      sample  289909   3.309 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.436           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.573           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  277623   3.456 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.606           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.426           ms/op
ClientPb.listUser                       sample  236670   4.054 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.323           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.280           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.913           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.622           ms/op
