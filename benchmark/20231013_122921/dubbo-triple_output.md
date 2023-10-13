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
# Warmup Iteration   1: 2.015 ops/ms
# Warmup Iteration   2: 5.530 ops/ms
# Warmup Iteration   3: 8.710 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 9.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.196 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (9.101, 9.196, 9.328), stdev = 0.118
  CI (99.9%): [7.052, 11.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 9.525 ops/ms
Iteration   1: 9.755 ops/ms
Iteration   2: 9.812 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.775 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (9.755, 9.775, 9.812), stdev = 0.033
  CI (99.9%): [9.180, 10.370] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.863 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 8.866 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.450 ops/ms
Iteration   3: 9.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.311 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (9.224, 9.311, 9.450), stdev = 0.121
  CI (99.9%): [7.098, 11.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.946 ops/ms
# Warmup Iteration   2: 7.106 ops/ms
# Warmup Iteration   3: 7.595 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.831 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (7.745, 7.831, 7.910), stdev = 0.083
  CI (99.9%): [6.318, 9.343] (assumes normal distribution)


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
# Warmup Iteration   1: 10.066 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.004 ms/op
Iteration   1: 3.565 ±(99.9%) 0.007 ms/op
Iteration   2: 3.436 ±(99.9%) 0.006 ms/op
Iteration   3: 3.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.482 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.436, 3.482, 3.565), stdev = 0.072
  CI (99.9%): [2.167, 4.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.720 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.004 ms/op
Iteration   1: 3.362 ±(99.9%) 0.004 ms/op
Iteration   2: 3.274 ±(99.9%) 0.004 ms/op
Iteration   3: 3.299 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.312 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.274, 3.312, 3.362), stdev = 0.046
  CI (99.9%): [2.480, 4.144] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.509 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.005 ms/op
Iteration   1: 3.376 ±(99.9%) 0.002 ms/op
Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
Iteration   3: 3.495 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.376, 3.426, 3.495), stdev = 0.062
  CI (99.9%): [2.293, 4.559] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.291 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.005 ms/op
Iteration   1: 4.131 ±(99.9%) 0.006 ms/op
Iteration   2: 4.144 ±(99.9%) 0.007 ms/op
Iteration   3: 4.005 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.093 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (4.005, 4.093, 4.144), stdev = 0.077
  CI (99.9%): [2.695, 5.492] (assumes normal distribution)


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
# Warmup Iteration   1: 9.579 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
Iteration   1: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   7.183 ms/op
                 createUser·p0.999:  16.565 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  18.353 ms/op
                 createUser·p0.9999: 20.723 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  18.842 ms/op
                 createUser·p0.9999: 23.421 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278734
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6421 
    [ 2.500,  5.000) = 262883 
    [ 5.000,  7.500) = 7684 
    [ 7.500, 10.000) = 1024 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     17.441 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.204 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.019 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.009 ms/op
Iteration   1: 3.367 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  19.367 ms/op
                 existUser·p0.9999: 21.611 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  20.808 ms/op
                 existUser·p0.9999: 25.036 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.453 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.450 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  21.398 ms/op
                 existUser·p0.9999: 30.203 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282563
  mean =      3.396 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6869 
    [ 2.500,  5.000) = 267048 
    [ 5.000,  7.500) = 6877 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     19.708 ms/op
     p(99.9900) =     26.287 ms/op
     p(99.9990) =     31.245 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 10.150 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.011 ms/op
Iteration   1: 3.618 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  14.139 ms/op
                 getUser·p0.9999: 27.404 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 20.686 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.222 ms/op
                 getUser·p0.9999: 23.500 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268903
  mean =      3.569 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7189 
    [ 2.500,  5.000) = 250390 
    [ 5.000,  7.500) = 8933 
    [ 7.500, 10.000) = 1501 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     23.352 ms/op
     p(99.9990) =     28.955 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.100 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.015 ms/op
Iteration   1: 4.119 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  20.009 ms/op
                 listUser·p0.9999: 23.928 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 4.134 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  15.693 ms/op
                 listUser·p0.9999: 20.163 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   3: 4.061 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.478 ms/op
                 listUser·p0.999:  14.046 ms/op
                 listUser·p0.9999: 23.418 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233798
  mean =      4.104 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 224641 
    [ 5.000,  7.500) = 6113 
    [ 7.500, 10.000) = 2047 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     28.683 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.196 ± 2.144  ops/ms
ClientPb.existUser                       thrpt       3   9.775 ± 0.595  ops/ms
ClientPb.getUser                         thrpt       3   9.311 ± 2.213  ops/ms
ClientPb.listUser                        thrpt       3   7.831 ± 1.513  ops/ms
ClientPb.createUser                       avgt       3   3.482 ± 1.316   ms/op
ClientPb.existUser                        avgt       3   3.312 ± 0.832   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 1.133   ms/op
ClientPb.listUser                         avgt       3   4.093 ± 1.398   ms/op
ClientPb.createUser                     sample  278734   3.442 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.311           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.441           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.445           ms/op
ClientPb.existUser                      sample  282563   3.396 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.708           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.457           ms/op
ClientPb.getUser                        sample  268903   3.569 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.498           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.352           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  233798   4.104 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.909           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
