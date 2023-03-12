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
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 5.900 ops/ms
# Warmup Iteration   3: 8.764 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.386 ±(99.9%) 1.898 ops/ms [Average]
  (min, avg, max) = (9.290, 9.386, 9.497), stdev = 0.104
  CI (99.9%): [7.489, 11.284] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.794 ops/ms
# Warmup Iteration   3: 9.519 ops/ms
Iteration   1: 10.221 ops/ms
Iteration   2: 9.800 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.933 ±(99.9%) 4.563 ops/ms [Average]
  (min, avg, max) = (9.776, 9.933, 10.221), stdev = 0.250
  CI (99.9%): [5.369, 14.496] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 8.711 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 8.986 ops/ms
Iteration   2: 9.560 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.414 ±(99.9%) 6.872 ops/ms [Average]
  (min, avg, max) = (8.986, 9.414, 9.696), stdev = 0.377
  CI (99.9%): [2.542, 16.286] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.010 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (7.919, 8.010, 8.079), stdev = 0.082
  CI (99.9%): [6.513, 9.507] (assumes normal distribution)


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
# Warmup Iteration   1: 9.506 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.004 ms/op
Iteration   1: 3.395 ±(99.9%) 0.008 ms/op
Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
Iteration   3: 3.402 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.349, 3.382, 3.402), stdev = 0.029
  CI (99.9%): [2.861, 3.903] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.853 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.007 ms/op
Iteration   1: 3.304 ±(99.9%) 0.008 ms/op
Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
Iteration   3: 3.199 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.222 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (3.163, 3.222, 3.304), stdev = 0.073
  CI (99.9%): [1.882, 4.562] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.624 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.008 ms/op
Iteration   1: 3.365 ±(99.9%) 0.010 ms/op
Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
Iteration   3: 3.364 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.364, 3.395, 3.455), stdev = 0.052
  CI (99.9%): [2.440, 4.349] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.848 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.008 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
Iteration   3: 3.944 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.947 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.941, 3.947, 3.956), stdev = 0.008
  CI (99.9%): [3.805, 4.089] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.097 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
Iteration   1: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.618 ms/op
                 createUser·p0.9999: 32.761 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  17.841 ms/op
                 createUser·p0.9999: 25.038 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  12.740 ms/op
                 createUser·p0.9999: 25.225 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289594
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12029 
    [ 2.500,  5.000) = 273355 
    [ 5.000,  7.500) = 3357 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.473 ms/op
     p(99.9000) =     12.078 ms/op
     p(99.9900) =     31.468 ms/op
     p(99.9990) =     33.342 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 7.869 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.007 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.491 ms/op
                 existUser·p0.999:  20.152 ms/op
                 existUser·p0.9999: 29.145 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 3.424 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  23.347 ms/op
                 existUser·p0.9999: 36.477 ms/op
                 existUser·p1.00:   37.224 ms/op

Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  21.111 ms/op
                 existUser·p0.9999: 28.306 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280907
  mean =      3.416 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16038 
    [ 2.500,  5.000) = 259631 
    [ 5.000,  7.500) = 4219 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     35.509 ms/op
     p(99.9990) =     37.106 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 8.811 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.016 ms/op
Iteration   1: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  22.788 ms/op
                 getUser·p0.9999: 33.394 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   3: 3.433 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  21.715 ms/op
                 getUser·p0.9999: 48.562 ms/op
                 getUser·p1.00:   49.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278325
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270122 
    [ 5.000, 10.000) = 7780 
    [10.000, 15.000) = 135 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 212 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     20.994 ms/op
     p(99.9900) =     44.182 ms/op
     p(99.9990) =     49.377 ms/op
     p(99.9999) =     49.480 ms/op
    p(100.0000) =     49.480 ms/op


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
# Warmup Iteration   1: 9.212 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.014 ms/op
Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242464
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 233990 
    [ 5.000,  7.500) = 6524 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     17.188 ms/op
     p(99.9900) =     25.682 ms/op
     p(99.9990) =     26.495 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.386 ± 1.898  ops/ms
ClientPb.existUser                       thrpt       3   9.933 ± 4.563  ops/ms
ClientPb.getUser                         thrpt       3   9.414 ± 6.872  ops/ms
ClientPb.listUser                        thrpt       3   8.010 ± 1.497  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 0.521   ms/op
ClientPb.existUser                        avgt       3   3.222 ± 1.340   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 0.954   ms/op
ClientPb.listUser                         avgt       3   3.947 ± 0.142   ms/op
ClientPb.createUser                     sample  289594   3.314 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.473           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.078           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  280907   3.416 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.509           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.224           ms/op
ClientPb.getUser                        sample  278325   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.859           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.994           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          49.480           ms/op
ClientPb.listUser                       sample  242464   3.958 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.188           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
