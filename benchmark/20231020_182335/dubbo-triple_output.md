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
# Warmup Iteration   1: 2.114 ops/ms
# Warmup Iteration   2: 5.303 ops/ms
# Warmup Iteration   3: 8.519 ops/ms
Iteration   1: 9.339 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.240 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (9.186, 9.240, 9.339), stdev = 0.086
  CI (99.9%): [7.663, 10.817] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 8.639 ops/ms
# Warmup Iteration   3: 9.433 ops/ms
Iteration   1: 9.716 ops/ms
Iteration   2: 9.759 ops/ms
Iteration   3: 9.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.705 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (9.638, 9.705, 9.759), stdev = 0.061
  CI (99.9%): [8.589, 10.820] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 8.737 ops/ms
# Warmup Iteration   3: 9.305 ops/ms
Iteration   1: 9.470 ops/ms
Iteration   2: 9.466 ops/ms
Iteration   3: 9.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.464 ±(99.9%) 0.144 ops/ms [Average]
  (min, avg, max) = (9.455, 9.464, 9.470), stdev = 0.008
  CI (99.9%): [9.319, 9.608] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.633 ops/ms
# Warmup Iteration   2: 7.169 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.812 ops/ms
Iteration   2: 7.734 ops/ms
Iteration   3: 7.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.801 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (7.734, 7.801, 7.857), stdev = 0.062
  CI (99.9%): [6.667, 8.935] (assumes normal distribution)


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
# Warmup Iteration   1: 11.147 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.011 ms/op
Iteration   1: 3.443 ±(99.9%) 0.004 ms/op
Iteration   2: 3.456 ±(99.9%) 0.008 ms/op
Iteration   3: 3.573 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.491 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.443, 3.491, 3.573), stdev = 0.072
  CI (99.9%): [2.180, 4.801] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.006 ms/op
Iteration   1: 3.319 ±(99.9%) 0.002 ms/op
Iteration   2: 3.283 ±(99.9%) 0.004 ms/op
Iteration   3: 3.246 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.246, 3.283, 3.319), stdev = 0.036
  CI (99.9%): [2.617, 3.948] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.068 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.004 ms/op
Iteration   1: 3.460 ±(99.9%) 0.003 ms/op
Iteration   2: 3.388 ±(99.9%) 0.005 ms/op
Iteration   3: 3.337 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (3.337, 3.395, 3.460), stdev = 0.062
  CI (99.9%): [2.269, 4.522] (assumes normal distribution)


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
# Warmup Iteration   1: 12.204 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.005 ms/op
Iteration   1: 4.183 ±(99.9%) 0.008 ms/op
Iteration   2: 4.146 ±(99.9%) 0.006 ms/op
Iteration   3: 4.119 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.149 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (4.119, 4.149, 4.183), stdev = 0.032
  CI (99.9%): [3.561, 4.738] (assumes normal distribution)


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
# Warmup Iteration   1: 8.898 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.011 ms/op
Iteration   1: 3.524 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  20.880 ms/op
                 createUser·p0.9999: 22.574 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   2: 3.542 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  22.502 ms/op
                 createUser·p0.9999: 25.033 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.650 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  22.948 ms/op
                 createUser·p0.9999: 27.762 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268865
  mean =      3.571 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2393 
    [ 2.500,  5.000) = 260215 
    [ 5.000,  7.500) = 4837 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.961 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 7.538 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
Iteration   1: 3.366 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 21.873 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.454 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  11.897 ms/op
                 existUser·p0.9999: 23.150 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.330 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  19.463 ms/op
                 existUser·p0.9999: 30.985 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281630
  mean =      3.408 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6026 
    [ 2.500,  5.000) = 271385 
    [ 5.000,  7.500) = 3316 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     29.883 ms/op
     p(99.9990) =     31.136 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 9.062 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.013 ms/op
Iteration   1: 3.515 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 31.490 ms/op
                 getUser·p1.00:   31.982 ms/op

Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  21.586 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.884 ms/op
                 getUser·p0.999:  19.715 ms/op
                 getUser·p0.9999: 27.008 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279418
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4972 
    [ 2.500,  5.000) = 267205 
    [ 5.000,  7.500) = 5923 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     29.952 ms/op
     p(99.9990) =     31.726 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 11.487 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.188 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.287 ms/op
                 listUser·p0.999:  17.915 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.236 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 17.819 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.059 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  15.995 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230682
  mean =      4.160 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 220771 
    [ 5.000,  7.500) = 8074 
    [ 7.500, 10.000) = 1043 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 292 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     22.450 ms/op
     p(99.9990) =     23.812 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.240 ± 1.577  ops/ms
ClientPb.existUser                       thrpt       3   9.705 ± 1.116  ops/ms
ClientPb.getUser                         thrpt       3   9.464 ± 0.144  ops/ms
ClientPb.listUser                        thrpt       3   7.801 ± 1.134  ops/ms
ClientPb.createUser                       avgt       3   3.491 ± 1.310   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 0.666   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 1.127   ms/op
ClientPb.listUser                         avgt       3   4.149 ± 0.589   ms/op
ClientPb.createUser                     sample  268865   3.571 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.601           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.234           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.182           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  281630   3.408 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.330           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.883           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  279418   3.433 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.952           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.982           ms/op
ClientPb.listUser                       sample  230682   4.160 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.376           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.450           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
