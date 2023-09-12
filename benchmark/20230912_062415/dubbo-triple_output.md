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
# Warmup Iteration   1: 2.046 ops/ms
# Warmup Iteration   2: 4.894 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 9.123 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.029 ±(99.9%) 3.076 ops/ms [Average]
  (min, avg, max) = (8.834, 9.029, 9.129), stdev = 0.169
  CI (99.9%): [5.952, 12.105] (assumes normal distribution)


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
# Warmup Iteration   1: 2.755 ops/ms
# Warmup Iteration   2: 8.225 ops/ms
# Warmup Iteration   3: 9.388 ops/ms
Iteration   1: 9.430 ops/ms
Iteration   2: 9.506 ops/ms
Iteration   3: 9.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.498 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (9.430, 9.498, 9.557), stdev = 0.064
  CI (99.9%): [8.329, 10.666] (assumes normal distribution)


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
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 8.607 ops/ms
# Warmup Iteration   3: 8.774 ops/ms
Iteration   1: 9.413 ops/ms
Iteration   2: 9.468 ops/ms
Iteration   3: 9.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.339 ±(99.9%) 3.232 ops/ms [Average]
  (min, avg, max) = (9.137, 9.339, 9.468), stdev = 0.177
  CI (99.9%): [6.107, 12.571] (assumes normal distribution)


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
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 6.951 ops/ms
# Warmup Iteration   3: 7.699 ops/ms
Iteration   1: 7.752 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.808 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (7.752, 7.808, 7.866), stdev = 0.057
  CI (99.9%): [6.766, 8.850] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.008 ms/op
Iteration   1: 3.592 ±(99.9%) 0.009 ms/op
Iteration   2: 3.481 ±(99.9%) 0.007 ms/op
Iteration   3: 3.437 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (3.437, 3.503, 3.592), stdev = 0.080
  CI (99.9%): [2.052, 4.955] (assumes normal distribution)


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
# Warmup Iteration   1: 8.948 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.004 ms/op
Iteration   1: 3.343 ±(99.9%) 0.003 ms/op
Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
Iteration   3: 3.466 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.395 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.343, 3.395, 3.466), stdev = 0.064
  CI (99.9%): [2.230, 4.561] (assumes normal distribution)


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
# Warmup Iteration   1: 9.913 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.006 ms/op
Iteration   1: 3.645 ±(99.9%) 0.004 ms/op
Iteration   2: 3.564 ±(99.9%) 0.006 ms/op
Iteration   3: 3.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.580 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.531, 3.580, 3.645), stdev = 0.059
  CI (99.9%): [2.508, 4.652] (assumes normal distribution)


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
# Warmup Iteration   1: 11.636 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.009 ms/op
Iteration   1: 4.130 ±(99.9%) 0.010 ms/op
Iteration   2: 4.075 ±(99.9%) 0.014 ms/op
Iteration   3: 4.185 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.130 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (4.075, 4.130, 4.185), stdev = 0.055
  CI (99.9%): [3.130, 5.129] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 12.609 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.015 ms/op
Iteration   1: 3.589 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  19.125 ms/op
                 createUser·p0.9999: 21.368 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   2: 3.531 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  20.132 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.580 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  23.508 ms/op
                 createUser·p0.9999: 26.282 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269017
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3104 
    [ 2.500,  5.000) = 257158 
    [ 5.000,  7.500) = 6790 
    [ 7.500, 10.000) = 1354 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     19.627 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     26.782 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 10.789 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 27.178 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  22.434 ms/op
                 existUser·p0.9999: 25.912 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.593 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   7.691 ms/op
                 existUser·p0.999:  21.885 ms/op
                 existUser·p0.9999: 28.606 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273828
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9347 
    [ 2.500,  5.000) = 254409 
    [ 5.000,  7.500) = 7823 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 111 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     27.029 ms/op
     p(99.9990) =     28.993 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 10.228 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.012 ms/op
Iteration   1: 3.783 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.374 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 26.018 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  22.874 ms/op
                 getUser·p0.9999: 26.994 ms/op
                 getUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265483
  mean =      3.614 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2241 
    [ 2.500,  5.000) = 251266 
    [ 5.000,  7.500) = 8645 
    [ 7.500, 10.000) = 2749 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.943 ms/op
     p(99.9900) =     26.065 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 12.007 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.720 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.014 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  20.921 ms/op
                 listUser·p0.9999: 23.437 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.234 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.113 ms/op
                 listUser·p0.9999: 22.392 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 4.117 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  15.029 ms/op
                 listUser·p0.9999: 18.157 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230775
  mean =      4.159 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 220493 
    [ 5.000,  7.500) = 6917 
    [ 7.500, 10.000) = 2364 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     16.595 ms/op
     p(99.9900) =     22.738 ms/op
     p(99.9990) =     23.878 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.029 ± 3.076  ops/ms
ClientPb.existUser                       thrpt       3   9.498 ± 1.169  ops/ms
ClientPb.getUser                         thrpt       3   9.339 ± 3.232  ops/ms
ClientPb.listUser                        thrpt       3   7.808 ± 1.042  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 1.451   ms/op
ClientPb.existUser                        avgt       3   3.395 ± 1.165   ms/op
ClientPb.getUser                          avgt       3   3.580 ± 1.072   ms/op
ClientPb.listUser                         avgt       3   4.130 ± 1.000   ms/op
ClientPb.createUser                     sample  269017   3.567 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.756           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  273828   3.504 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.209           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.450           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.029           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  265483   3.614 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.692           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.065           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.853           ms/op
ClientPb.listUser                       sample  230775   4.159 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.935           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.738           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.921           ms/op
