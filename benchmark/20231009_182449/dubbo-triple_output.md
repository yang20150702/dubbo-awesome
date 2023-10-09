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
# Warmup Iteration   1: 2.019 ops/ms
# Warmup Iteration   2: 4.922 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.884 ops/ms
Iteration   2: 8.734 ops/ms
Iteration   3: 9.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.954 ±(99.9%) 4.775 ops/ms [Average]
  (min, avg, max) = (8.734, 8.954, 9.243), stdev = 0.262
  CI (99.9%): [4.178, 13.729] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.864 ops/ms
# Warmup Iteration   2: 8.501 ops/ms
# Warmup Iteration   3: 9.116 ops/ms
Iteration   1: 9.356 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.479 ±(99.9%) 2.452 ops/ms [Average]
  (min, avg, max) = (9.356, 9.479, 9.623), stdev = 0.134
  CI (99.9%): [7.027, 11.931] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 8.667 ops/ms
Iteration   1: 9.010 ops/ms
Iteration   2: 8.940 ops/ms
Iteration   3: 8.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.873 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (8.669, 8.873, 9.010), stdev = 0.180
  CI (99.9%): [5.593, 12.153] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.483 ops/ms
# Warmup Iteration   2: 6.562 ops/ms
# Warmup Iteration   3: 7.366 ops/ms
Iteration   1: 7.469 ops/ms
Iteration   2: 7.423 ops/ms
Iteration   3: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.459 ±(99.9%) 0.577 ops/ms [Average]
  (min, avg, max) = (7.423, 7.459, 7.484), stdev = 0.032
  CI (99.9%): [6.882, 8.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.501 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.005 ms/op
Iteration   1: 3.642 ±(99.9%) 0.006 ms/op
Iteration   2: 3.604 ±(99.9%) 0.004 ms/op
Iteration   3: 3.667 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.637 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.604, 3.637, 3.667), stdev = 0.032
  CI (99.9%): [3.060, 4.215] (assumes normal distribution)


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
# Warmup Iteration   1: 10.676 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.005 ms/op
Iteration   1: 3.407 ±(99.9%) 0.004 ms/op
Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.437 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.407, 3.437, 3.461), stdev = 0.028
  CI (99.9%): [2.932, 3.942] (assumes normal distribution)


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
# Warmup Iteration   1: 9.109 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.003 ms/op
Iteration   1: 3.606 ±(99.9%) 0.002 ms/op
Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
Iteration   3: 3.632 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.625 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (3.606, 3.625, 3.636), stdev = 0.016
  CI (99.9%): [3.335, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 11.050 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.691 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.005 ms/op
Iteration   1: 4.347 ±(99.9%) 0.005 ms/op
Iteration   2: 4.269 ±(99.9%) 0.007 ms/op
Iteration   3: 4.161 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.259 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (4.161, 4.259, 4.347), stdev = 0.094
  CI (99.9%): [2.551, 5.967] (assumes normal distribution)


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
# Warmup Iteration   1: 10.441 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.015 ms/op
Iteration   1: 3.562 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 23.413 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   2: 3.684 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  22.088 ms/op
                 createUser·p0.9999: 26.323 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  19.989 ms/op
                 createUser·p0.9999: 29.003 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265696
  mean =      3.612 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5298 
    [ 2.500,  5.000) = 251945 
    [ 5.000,  7.500) = 6720 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     27.572 ms/op
     p(99.9990) =     30.059 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 7.802 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
Iteration   1: 3.589 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  18.696 ms/op
                 existUser·p0.9999: 21.636 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   2: 3.501 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  21.502 ms/op
                 existUser·p0.9999: 26.468 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.577 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 27.002 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 269874
  mean =      3.555 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3602 
    [ 2.500,  5.000) = 256387 
    [ 5.000,  7.500) = 8178 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.088 ms/op
     p(99.9000) =     18.723 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     27.857 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 8.705 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.014 ms/op
Iteration   1: 3.669 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   5.482 ms/op
                 getUser·p0.99:   7.880 ms/op
                 getUser·p0.999:  18.705 ms/op
                 getUser·p0.9999: 27.108 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.118 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.866 ms/op
                 getUser·p0.9999: 23.244 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.652 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  22.372 ms/op
                 getUser·p0.9999: 27.820 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265356
  mean =      3.614 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1711 
    [ 2.500,  5.000) = 253525 
    [ 5.000,  7.500) = 8318 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     27.114 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 11.200 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.014 ms/op
Iteration   1: 4.272 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.955 ms/op
                 listUser·p0.999:  22.548 ms/op
                 listUser·p0.9999: 25.134 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 4.353 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 17.999 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 4.260 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.145 ms/op
                 listUser·p0.999:  17.168 ms/op
                 listUser·p0.9999: 21.134 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223404
  mean =      4.294 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 211088 
    [ 5.000,  7.500) = 9290 
    [ 7.500, 10.000) = 2051 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 281 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     24.783 ms/op
     p(99.9990) =     25.503 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.954 ± 4.775  ops/ms
ClientPb.existUser                       thrpt       3   9.479 ± 2.452  ops/ms
ClientPb.getUser                         thrpt       3   8.873 ± 3.280  ops/ms
ClientPb.listUser                        thrpt       3   7.459 ± 0.577  ops/ms
ClientPb.createUser                       avgt       3   3.637 ± 0.577   ms/op
ClientPb.existUser                        avgt       3   3.437 ± 0.505   ms/op
ClientPb.getUser                          avgt       3   3.625 ± 0.289   ms/op
ClientPb.listUser                         avgt       3   4.259 ± 1.708   ms/op
ClientPb.createUser                     sample  265696   3.612 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.572           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372           ms/op
ClientPb.existUser                      sample  269874   3.555 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.088           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.723           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.575           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.343           ms/op
ClientPb.getUser                        sample  265356   3.614 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.848           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.114           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.440           ms/op
ClientPb.listUser                       sample  223404   4.294 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.542           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.783           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526           ms/op
