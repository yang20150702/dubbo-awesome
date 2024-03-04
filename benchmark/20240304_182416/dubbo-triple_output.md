# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ops/ms
# Warmup Iteration   2: 12.320 ops/ms
# Warmup Iteration   3: 12.604 ops/ms
Iteration   1: 12.915 ops/ms
Iteration   2: 12.963 ops/ms
Iteration   3: 12.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.957 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (12.915, 12.957, 12.994), stdev = 0.040
  CI (99.9%): [12.230, 13.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 13.260 ops/ms
# Warmup Iteration   3: 13.342 ops/ms
Iteration   1: 13.259 ops/ms
Iteration   2: 13.342 ops/ms
Iteration   3: 13.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.256 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (13.166, 13.256, 13.342), stdev = 0.088
  CI (99.9%): [11.650, 14.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ops/ms
# Warmup Iteration   2: 12.839 ops/ms
# Warmup Iteration   3: 12.870 ops/ms
Iteration   1: 12.236 ops/ms
Iteration   2: 12.627 ops/ms
Iteration   3: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.520 ±(99.9%) 4.523 ops/ms [Average]
  (min, avg, max) = (12.236, 12.520, 12.696), stdev = 0.248
  CI (99.9%): [7.996, 17.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.374 ops/ms
# Warmup Iteration   2: 10.148 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.659 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (10.539, 10.659, 10.839), stdev = 0.159
  CI (99.9%): [7.762, 13.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.606 ±(99.9%) 0.010 ms/op
Iteration   1: 2.522 ±(99.9%) 0.009 ms/op
Iteration   2: 2.501 ±(99.9%) 0.009 ms/op
Iteration   3: 2.543 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.501, 2.522, 2.543), stdev = 0.021
  CI (99.9%): [2.140, 2.905] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.008 ms/op
Iteration   1: 2.427 ±(99.9%) 0.007 ms/op
Iteration   2: 2.453 ±(99.9%) 0.007 ms/op
Iteration   3: 2.455 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.427, 2.445, 2.455), stdev = 0.015
  CI (99.9%): [2.163, 2.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.008 ms/op
Iteration   1: 2.501 ±(99.9%) 0.009 ms/op
Iteration   2: 2.487 ±(99.9%) 0.009 ms/op
Iteration   3: 2.516 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.487, 2.501, 2.516), stdev = 0.015
  CI (99.9%): [2.232, 2.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.012 ms/op
Iteration   1: 2.951 ±(99.9%) 0.012 ms/op
Iteration   2: 3.102 ±(99.9%) 0.010 ms/op
Iteration   3: 3.002 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 1.397 ms/op [Average]
  (min, avg, max) = (2.951, 3.018, 3.102), stdev = 0.077
  CI (99.9%): [1.621, 4.415] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.799 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.007 ms/op
Iteration   1: 2.573 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.500 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  13.955 ms/op
                 createUser·p0.9999: 16.124 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 15.483 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   3: 2.568 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.442 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 16.533 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373793
  mean =      2.566 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 182917 
    [ 2.500,  3.750) = 172667 
    [ 3.750,  5.000) = 14828 
    [ 5.000,  6.250) = 1672 
    [ 6.250,  7.500) = 547 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 112 
    [15.000, 16.250) = 95 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =     10.686 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     17.189 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   2.372 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.195 ms/op
                 existUser·p0.999:  12.363 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 2.434 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.515 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 2.435 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.367 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  9.227 ms/op
                 existUser·p0.9999: 13.652 ms/op
                 existUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392476
  mean =      2.444 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227465 
    [ 2.500,  5.000) = 161767 
    [ 5.000,  7.500) = 2651 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      2.376 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      9.298 ms/op
     p(99.9900) =     18.407 ms/op
     p(99.9990) =     20.089 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.742 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.008 ms/op
Iteration   1: 2.689 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.353 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  13.998 ms/op
                 getUser·p0.9999: 19.307 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.370 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.910 ms/op
                 getUser·p0.99:   5.252 ms/op
                 getUser·p0.999:  9.493 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 2.672 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.348 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  11.868 ms/op
                 getUser·p0.9999: 18.974 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 359827
  mean =      2.666 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166125 
    [ 2.500,  5.000) = 189040 
    [ 5.000,  7.500) = 3787 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     11.687 ms/op
     p(99.9900) =     18.908 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.010 ms/op
Iteration   1: 3.323 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.407 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.280 ms/op
                 listUser·p0.999:  12.519 ms/op
                 listUser·p0.9999: 15.022 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.105 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  11.717 ms/op
                 listUser·p0.9999: 14.647 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.228 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.385 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  11.386 ms/op
                 listUser·p0.9999: 14.640 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 298174
  mean =      3.216 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 78258 
    [ 2.500,  3.750) = 150678 
    [ 3.750,  5.000) = 54349 
    [ 5.000,  6.250) = 9877 
    [ 6.250,  7.500) = 2374 
    [ 7.500,  8.750) = 1043 
    [ 8.750, 10.000) = 516 
    [10.000, 11.250) = 264 
    [11.250, 12.500) = 191 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     14.814 ms/op
     p(99.9990) =     16.503 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.957 ± 0.728  ops/ms
ClientPb.existUser                       thrpt       3  13.256 ± 1.606  ops/ms
ClientPb.getUser                         thrpt       3  12.520 ± 4.523  ops/ms
ClientPb.listUser                        thrpt       3  10.659 ± 2.896  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.383   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.282   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.269   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 1.397   ms/op
ClientPb.createUser                     sample  373793   2.566 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.369           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.686           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.958           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.793           ms/op
ClientPb.existUser                      sample  392476   2.444 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.425           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.376           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.298           ms/op
ClientPb.existUser:existUser·p0.9999    sample          18.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.972           ms/op
ClientPb.getUser                        sample  359827   2.666 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.687           ms/op
ClientPb.getUser:getUser·p0.9999        sample          18.908           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.120           ms/op
ClientPb.listUser                       sample  298174   3.216 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.385           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.056           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.862           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.814           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.186           ms/op
