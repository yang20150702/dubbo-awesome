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
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 5.020 ops/ms
# Warmup Iteration   3: 8.660 ops/ms
Iteration   1: 8.990 ops/ms
Iteration   2: 9.492 ops/ms
Iteration   3: 9.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.171 ±(99.9%) 5.077 ops/ms [Average]
  (min, avg, max) = (8.990, 9.171, 9.492), stdev = 0.278
  CI (99.9%): [4.094, 14.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 8.144 ops/ms
# Warmup Iteration   3: 9.269 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.676 ±(99.9%) 4.979 ops/ms [Average]
  (min, avg, max) = (9.513, 9.676, 9.991), stdev = 0.273
  CI (99.9%): [4.697, 14.655] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 7.882 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.613 ops/ms
Iteration   3: 9.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.490 ±(99.9%) 4.603 ops/ms [Average]
  (min, avg, max) = (9.200, 9.490, 9.657), stdev = 0.252
  CI (99.9%): [4.887, 14.093] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.700 ops/ms
# Warmup Iteration   2: 7.150 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.211 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (8.113, 8.211, 8.356), stdev = 0.128
  CI (99.9%): [5.871, 10.550] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.301 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.005 ms/op
Iteration   1: 3.382 ±(99.9%) 0.005 ms/op
Iteration   2: 3.446 ±(99.9%) 0.008 ms/op
Iteration   3: 3.318 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.318, 3.382, 3.446), stdev = 0.064
  CI (99.9%): [2.218, 4.547] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.509 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
Iteration   1: 3.338 ±(99.9%) 0.006 ms/op
Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
Iteration   3: 3.296 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.247, 3.294, 3.338), stdev = 0.046
  CI (99.9%): [2.463, 4.124] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.335 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.006 ms/op
Iteration   1: 3.465 ±(99.9%) 0.009 ms/op
Iteration   2: 3.422 ±(99.9%) 0.005 ms/op
Iteration   3: 3.455 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.422, 3.448, 3.465), stdev = 0.022
  CI (99.9%): [3.043, 3.852] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.572 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.010 ms/op
Iteration   1: 4.014 ±(99.9%) 0.010 ms/op
Iteration   2: 4.132 ±(99.9%) 0.005 ms/op
Iteration   3: 3.908 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.018 ±(99.9%) 2.041 ms/op [Average]
  (min, avg, max) = (3.908, 4.018, 4.132), stdev = 0.112
  CI (99.9%): [1.977, 6.059] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.983 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
Iteration   1: 3.384 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  18.070 ms/op
                 createUser·p0.9999: 23.570 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.831 ms/op
                 createUser·p0.9999: 22.527 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.437 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  17.463 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283009
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11094 
    [ 2.500,  5.000) = 266432 
    [ 5.000,  7.500) = 4404 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     22.590 ms/op
     p(99.9990) =     23.981 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.922 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.067 ms/op
                 existUser·p0.999:  12.601 ms/op
                 existUser·p0.9999: 29.884 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  8.578 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.299 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  18.975 ms/op
                 existUser·p0.9999: 29.775 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291988
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13945 
    [ 2.500,  5.000) = 272713 
    [ 5.000,  7.500) = 4562 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.596 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     29.347 ms/op
     p(99.9990) =     30.550 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 9.917 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
Iteration   1: 3.568 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  16.788 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  21.803 ms/op
                 getUser·p0.9999: 33.454 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  18.872 ms/op
                 getUser·p0.9999: 26.111 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271983
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7686 
    [ 2.500,  5.000) = 254815 
    [ 5.000,  7.500) = 8060 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     34.068 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.076 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.014 ms/op
Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  20.039 ms/op
                 listUser·p0.9999: 23.523 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.974 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.986 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242163
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 233627 
    [ 5.000,  7.500) = 6885 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     23.874 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.171 ± 5.077  ops/ms
ClientPb.existUser                       thrpt       3   9.676 ± 4.979  ops/ms
ClientPb.getUser                         thrpt       3   9.490 ± 4.603  ops/ms
ClientPb.listUser                        thrpt       3   8.211 ± 2.340  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 1.164   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 0.831   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 0.405   ms/op
ClientPb.listUser                         avgt       3   4.018 ± 2.041   ms/op
ClientPb.createUser                     sample  283009   3.391 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.590           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.347           ms/op
ClientPb.existUser                      sample  291988   3.285 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.596           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.347           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  271983   3.529 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.133           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.145           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  242163   3.963 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.052           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.905           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
