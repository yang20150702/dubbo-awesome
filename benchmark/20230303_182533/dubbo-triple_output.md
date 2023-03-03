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
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.180 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.817 ops/ms
Iteration   2: 8.994 ops/ms
Iteration   3: 9.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.950 ±(99.9%) 2.154 ops/ms [Average]
  (min, avg, max) = (8.817, 8.950, 9.041), stdev = 0.118
  CI (99.9%): [6.797, 11.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.252 ops/ms
# Warmup Iteration   2: 8.797 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 10.009 ops/ms
Iteration   3: 9.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.728 ±(99.9%) 6.994 ops/ms [Average]
  (min, avg, max) = (9.291, 9.728, 10.009), stdev = 0.383
  CI (99.9%): [2.734, 16.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.448 ops/ms
# Warmup Iteration   2: 8.082 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.146 ops/ms
Iteration   2: 9.649 ops/ms
Iteration   3: 9.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.413 ±(99.9%) 4.615 ops/ms [Average]
  (min, avg, max) = (9.146, 9.413, 9.649), stdev = 0.253
  CI (99.9%): [4.798, 14.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 6.989 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 7.943 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.933 ±(99.9%) 0.344 ops/ms [Average]
  (min, avg, max) = (7.911, 7.933, 7.944), stdev = 0.019
  CI (99.9%): [7.589, 8.276] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.261 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.005 ms/op
Iteration   1: 3.358 ±(99.9%) 0.007 ms/op
Iteration   2: 3.325 ±(99.9%) 0.011 ms/op
Iteration   3: 3.479 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.388 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (3.325, 3.388, 3.479), stdev = 0.081
  CI (99.9%): [1.909, 4.866] (assumes normal distribution)


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
# Warmup Iteration   1: 9.740 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.001 ms/op
Iteration   1: 3.265 ±(99.9%) 0.005 ms/op
Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
Iteration   3: 3.299 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.245 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.172, 3.245, 3.299), stdev = 0.065
  CI (99.9%): [2.052, 4.439] (assumes normal distribution)


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
# Warmup Iteration   1: 8.854 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.003 ms/op
Iteration   1: 3.394 ±(99.9%) 0.005 ms/op
Iteration   2: 3.350 ±(99.9%) 0.011 ms/op
Iteration   3: 3.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.350, 3.389, 3.424), stdev = 0.038
  CI (99.9%): [2.705, 4.074] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.727 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.010 ms/op
Iteration   1: 3.970 ±(99.9%) 0.013 ms/op
Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
Iteration   3: 3.980 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.924, 3.958, 3.980), stdev = 0.030
  CI (99.9%): [3.410, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 9.994 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 22.107 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.589 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  21.755 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  17.652 ms/op
                 createUser·p0.9999: 27.549 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275230
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6448 
    [ 2.500,  5.000) = 262784 
    [ 5.000,  7.500) = 4857 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     18.164 ms/op
     p(99.9900) =     26.639 ms/op
     p(99.9990) =     27.934 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.325 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
Iteration   1: 3.335 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  20.055 ms/op
                 existUser·p0.9999: 23.606 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.746 ms/op
                 existUser·p0.999:  21.859 ms/op
                 existUser·p0.9999: 25.769 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  17.605 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285634
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14342 
    [ 2.500,  5.000) = 263300 
    [ 5.000,  7.500) = 6929 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     17.597 ms/op
     p(99.9900) =     26.589 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 9.857 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.012 ms/op
Iteration   1: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  10.292 ms/op
                 getUser·p0.9999: 22.617 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.068 ms/op
                 getUser·p0.999:  21.944 ms/op
                 getUser·p0.9999: 24.572 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.453 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  25.012 ms/op
                 getUser·p0.9999: 29.262 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277486
  mean =      3.460 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7966 
    [ 2.500,  5.000) = 260028 
    [ 5.000,  7.500) = 8260 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     29.644 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 11.175 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.014 ms/op
Iteration   1: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 26.309 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 29.093 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243052
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 236328 
    [ 5.000,  7.500) = 4716 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.006 ms/op
     p(99.9900) =     26.489 ms/op
     p(99.9990) =     29.627 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.950 ± 2.154  ops/ms
ClientPb.existUser                       thrpt       3   9.728 ± 6.994  ops/ms
ClientPb.getUser                         thrpt       3   9.413 ± 4.615  ops/ms
ClientPb.listUser                        thrpt       3   7.933 ± 0.344  ops/ms
ClientPb.createUser                       avgt       3   3.388 ± 1.479   ms/op
ClientPb.existUser                        avgt       3   3.245 ± 1.194   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 0.684   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 0.548   ms/op
ClientPb.createUser                     sample  275230   3.486 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.164           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  285634   3.360 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.597           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.589           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.622           ms/op
ClientPb.getUser                        sample  277486   3.460 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.743           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.632           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.705           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  243052   3.953 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.006           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.489           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
