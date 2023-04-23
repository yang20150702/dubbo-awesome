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
# Warmup Iteration   1: 2.249 ops/ms
# Warmup Iteration   2: 5.572 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.068 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.277 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (9.068, 9.277, 9.400), stdev = 0.182
  CI (99.9%): [5.954, 12.601] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 8.138 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 9.701 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.690 ±(99.9%) 4.641 ops/ms [Average]
  (min, avg, max) = (9.430, 9.690, 9.938), stdev = 0.254
  CI (99.9%): [5.049, 14.330] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.941 ops/ms
# Warmup Iteration   2: 8.020 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.425 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.394 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (9.337, 9.394, 9.425), stdev = 0.050
  CI (99.9%): [8.485, 10.304] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 6.762 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 7.837 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.903 ±(99.9%) 4.174 ops/ms [Average]
  (min, avg, max) = (7.714, 7.903, 8.157), stdev = 0.229
  CI (99.9%): [3.729, 12.076] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.342 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.007 ms/op
Iteration   1: 3.464 ±(99.9%) 0.003 ms/op
Iteration   2: 3.312 ±(99.9%) 0.002 ms/op
Iteration   3: 3.276 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.351 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (3.276, 3.351, 3.464), stdev = 0.100
  CI (99.9%): [1.528, 5.174] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.675 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.006 ms/op
Iteration   1: 3.349 ±(99.9%) 0.007 ms/op
Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
Iteration   3: 3.309 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.296 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.230, 3.296, 3.349), stdev = 0.061
  CI (99.9%): [2.189, 4.403] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.396 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.001 ms/op
Iteration   1: 3.599 ±(99.9%) 0.007 ms/op
Iteration   2: 3.390 ±(99.9%) 0.008 ms/op
Iteration   3: 3.606 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.531 ±(99.9%) 2.241 ms/op [Average]
  (min, avg, max) = (3.390, 3.531, 3.606), stdev = 0.123
  CI (99.9%): [1.290, 5.772] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.831 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.008 ms/op
Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
Iteration   3: 4.025 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.906, 3.959, 4.025), stdev = 0.061
  CI (99.9%): [2.855, 5.063] (assumes normal distribution)


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
# Warmup Iteration   1: 10.161 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.010 ms/op
Iteration   1: 3.716 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   6.316 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  18.610 ms/op
                 createUser·p0.9999: 31.437 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  20.539 ms/op
                 createUser·p0.9999: 24.677 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.393 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  14.760 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274918
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4218 
    [ 2.500,  5.000) = 260727 
    [ 5.000,  7.500) = 8366 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.091 ms/op
     p(99.9900) =     30.344 ms/op
     p(99.9990) =     31.810 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 7.592 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
Iteration   1: 3.256 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  12.770 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   2: 3.336 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  19.107 ms/op
                 existUser·p0.9999: 24.327 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.483 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  16.340 ms/op
                 existUser·p0.9999: 24.177 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286022
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6587 
    [ 2.500,  5.000) = 273791 
    [ 5.000,  7.500) = 4844 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     24.032 ms/op
     p(99.9990) =     24.974 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 8.647 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.012 ms/op
Iteration   1: 3.506 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  19.040 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.529 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  9.753 ms/op
                 getUser·p0.9999: 27.359 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.966 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  18.975 ms/op
                 getUser·p0.9999: 34.116 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276352
  mean =      3.474 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5182 
    [ 2.500,  5.000) = 262331 
    [ 5.000,  7.500) = 7517 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     32.923 ms/op
     p(99.9990) =     35.158 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.481 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.948 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 21.903 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 4.184 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  14.804 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 4.110 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.143 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232157
  mean =      4.133 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 220985 
    [ 5.000,  7.500) = 8574 
    [ 7.500, 10.000) = 1761 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     15.054 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     23.235 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.277 ± 3.324  ops/ms
ClientPb.existUser                       thrpt       3   9.690 ± 4.641  ops/ms
ClientPb.getUser                         thrpt       3   9.394 ± 0.910  ops/ms
ClientPb.listUser                        thrpt       3   7.903 ± 4.174  ops/ms
ClientPb.createUser                       avgt       3   3.351 ± 1.823   ms/op
ClientPb.existUser                        avgt       3   3.296 ± 1.107   ms/op
ClientPb.getUser                          avgt       3   3.531 ± 2.241   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 1.104   ms/op
ClientPb.createUser                     sample  274918   3.490 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.091           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  286022   3.356 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.687           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.032           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.133           ms/op
ClientPb.getUser                        sample  276352   3.474 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.912           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.778           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.923           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  232157   4.133 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.054           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.316           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
