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
# Warmup Iteration   1: 2.039 ops/ms
# Warmup Iteration   2: 5.018 ops/ms
# Warmup Iteration   3: 8.687 ops/ms
Iteration   1: 8.750 ops/ms
Iteration   2: 9.146 ops/ms
Iteration   3: 8.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.957 ±(99.9%) 3.619 ops/ms [Average]
  (min, avg, max) = (8.750, 8.957, 9.146), stdev = 0.198
  CI (99.9%): [5.338, 12.576] (assumes normal distribution)


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
# Warmup Iteration   1: 2.752 ops/ms
# Warmup Iteration   2: 8.671 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 9.384 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.394 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (9.274, 9.394, 9.524), stdev = 0.125
  CI (99.9%): [7.110, 11.679] (assumes normal distribution)


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
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 8.325 ops/ms
# Warmup Iteration   3: 8.814 ops/ms
Iteration   1: 9.159 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.128 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (9.029, 9.128, 9.195), stdev = 0.087
  CI (99.9%): [7.538, 10.717] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.669 ops/ms
# Warmup Iteration   2: 6.946 ops/ms
# Warmup Iteration   3: 7.335 ops/ms
Iteration   1: 7.739 ops/ms
Iteration   2: 7.244 ops/ms
Iteration   3: 7.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.479 ±(99.9%) 4.535 ops/ms [Average]
  (min, avg, max) = (7.244, 7.479, 7.739), stdev = 0.249
  CI (99.9%): [2.944, 12.015] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.532 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.004 ms/op
Iteration   1: 3.581 ±(99.9%) 0.006 ms/op
Iteration   2: 3.447 ±(99.9%) 0.007 ms/op
Iteration   3: 3.608 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 1.569 ms/op [Average]
  (min, avg, max) = (3.447, 3.546, 3.608), stdev = 0.086
  CI (99.9%): [1.977, 5.114] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.415 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.457 ±(99.9%) 0.004 ms/op
Iteration   3: 3.396 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.401 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.350, 3.401, 3.457), stdev = 0.054
  CI (99.9%): [2.424, 4.378] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.439 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.004 ms/op
Iteration   1: 3.508 ±(99.9%) 0.003 ms/op
Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
Iteration   3: 3.561 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.530 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.508, 3.530, 3.561), stdev = 0.028
  CI (99.9%): [3.024, 4.035] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.951 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.005 ms/op
Iteration   1: 4.231 ±(99.9%) 0.008 ms/op
Iteration   2: 4.209 ±(99.9%) 0.005 ms/op
Iteration   3: 4.167 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.202 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (4.167, 4.202, 4.231), stdev = 0.033
  CI (99.9%): [3.605, 4.800] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.498 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.012 ms/op
Iteration   1: 3.525 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  20.169 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 24.396 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.560 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  21.728 ms/op
                 createUser·p0.9999: 33.325 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273224
  mean =      3.516 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8863 
    [ 2.500,  5.000) = 255526 
    [ 5.000,  7.500) = 7298 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     31.847 ms/op
     p(99.9990) =     33.834 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.165 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.008 ms/op
Iteration   1: 3.430 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  20.329 ms/op
                 existUser·p0.9999: 23.103 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.555 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  14.448 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.975 ms/op
                 existUser·p0.999:  23.362 ms/op
                 existUser·p0.9999: 29.619 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274298
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5038 
    [ 2.500,  5.000) = 259699 
    [ 5.000,  7.500) = 7931 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     28.396 ms/op
     p(99.9990) =     30.353 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.827 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
Iteration   1: 3.564 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  21.809 ms/op
                 getUser·p0.9999: 24.155 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.492 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  22.921 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.495 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  20.414 ms/op
                 getUser·p0.9999: 29.149 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272893
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3376 
    [ 2.500,  5.000) = 260615 
    [ 5.000,  7.500) = 7217 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     28.129 ms/op
     p(99.9990) =     29.595 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 10.159 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.013 ms/op
Iteration   1: 4.260 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  21.491 ms/op
                 listUser·p0.9999: 25.887 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 4.152 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.869 ms/op
                 listUser·p0.999:  16.236 ms/op
                 listUser·p0.9999: 18.805 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.286 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226768
  mean =      4.232 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 212589 
    [ 5.000,  7.500) = 10312 
    [ 7.500, 10.000) = 2744 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     16.634 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.286 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.957 ± 3.619  ops/ms
ClientPb.existUser                       thrpt       3   9.394 ± 2.285  ops/ms
ClientPb.getUser                         thrpt       3   9.128 ± 1.590  ops/ms
ClientPb.listUser                        thrpt       3   7.479 ± 4.535  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 1.569   ms/op
ClientPb.existUser                        avgt       3   3.401 ± 0.977   ms/op
ClientPb.getUser                          avgt       3   3.530 ± 0.506   ms/op
ClientPb.listUser                         avgt       3   4.202 ± 0.598   ms/op
ClientPb.createUser                     sample  273224   3.516 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.266           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.847           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  274298   3.497 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.321           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.153           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.396           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  272893   3.517 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.129           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  226768   4.232 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
