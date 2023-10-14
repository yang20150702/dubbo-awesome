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
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 5.676 ops/ms
# Warmup Iteration   3: 8.470 ops/ms
Iteration   1: 8.946 ops/ms
Iteration   2: 9.141 ops/ms
Iteration   3: 9.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.080 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (8.946, 9.080, 9.154), stdev = 0.117
  CI (99.9%): [6.952, 11.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 8.664 ops/ms
# Warmup Iteration   3: 9.156 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.553 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.575 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (9.463, 9.575, 9.707), stdev = 0.123
  CI (99.9%): [7.324, 11.826] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 7.782 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 8.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.124 ±(99.9%) 4.527 ops/ms [Average]
  (min, avg, max) = (8.839, 9.124, 9.285), stdev = 0.248
  CI (99.9%): [4.598, 13.651] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.764 ops/ms
# Warmup Iteration   2: 7.149 ops/ms
# Warmup Iteration   3: 7.600 ops/ms
Iteration   1: 7.693 ops/ms
Iteration   2: 7.619 ops/ms
Iteration   3: 7.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.732 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (7.619, 7.732, 7.885), stdev = 0.137
  CI (99.9%): [5.229, 10.236] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.997 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.004 ms/op
Iteration   1: 3.649 ±(99.9%) 0.006 ms/op
Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
Iteration   3: 3.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.567 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.506, 3.567, 3.649), stdev = 0.074
  CI (99.9%): [2.224, 4.910] (assumes normal distribution)


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
# Warmup Iteration   1: 10.455 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.004 ms/op
Iteration   1: 3.363 ±(99.9%) 0.004 ms/op
Iteration   2: 3.205 ±(99.9%) 0.004 ms/op
Iteration   3: 3.396 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.321 ±(99.9%) 1.865 ms/op [Average]
  (min, avg, max) = (3.205, 3.321, 3.396), stdev = 0.102
  CI (99.9%): [1.456, 5.187] (assumes normal distribution)


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
# Warmup Iteration   1: 7.865 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.003 ms/op
Iteration   1: 3.537 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.004 ms/op
Iteration   3: 3.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.494 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.465, 3.494, 3.537), stdev = 0.038
  CI (99.9%): [2.801, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 10.840 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.009 ms/op
Iteration   1: 4.173 ±(99.9%) 0.007 ms/op
Iteration   2: 4.277 ±(99.9%) 0.007 ms/op
Iteration   3: 4.152 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.201 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (4.152, 4.201, 4.277), stdev = 0.067
  CI (99.9%): [2.984, 5.417] (assumes normal distribution)


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
# Warmup Iteration   1: 9.926 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.014 ms/op
Iteration   1: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  19.645 ms/op
                 createUser·p0.9999: 24.702 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.493 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  21.643 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  18.679 ms/op
                 createUser·p0.9999: 25.874 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273238
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3649 
    [ 2.500,  5.000) = 261384 
    [ 5.000,  7.500) = 6404 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     24.860 ms/op
     p(99.9990) =     26.520 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 8.661 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.011 ms/op
Iteration   1: 3.430 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  20.499 ms/op
                 existUser·p0.9999: 22.883 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  22.872 ms/op
                 existUser·p0.9999: 40.983 ms/op
                 existUser·p1.00:   42.140 ms/op

Iteration   3: 3.411 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  23.040 ms/op
                 existUser·p0.9999: 28.069 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279345
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 269526 
    [ 5.000, 10.000) = 9306 
    [10.000, 15.000) = 188 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 192 
    [25.000, 30.000) = 90 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     21.091 ms/op
     p(99.9900) =     38.998 ms/op
     p(99.9990) =     41.787 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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
# Warmup Iteration   1: 9.814 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.012 ms/op
Iteration   1: 3.596 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.510 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 23.259 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.658 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  20.124 ms/op
                 getUser·p0.9999: 22.979 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267462
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4109 
    [ 2.500,  5.000) = 253178 
    [ 5.000,  7.500) = 7434 
    [ 7.500, 10.000) = 1907 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     18.073 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 11.407 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.014 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 23.961 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  16.652 ms/op
                 listUser·p0.9999: 26.193 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 4.159 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  15.322 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231164
  mean =      4.153 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 220073 
    [ 5.000,  7.500) = 7322 
    [ 7.500, 10.000) = 2562 
    [10.000, 12.500) = 459 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     27.537 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.080 ± 2.128  ops/ms
ClientPb.existUser                       thrpt       3   9.575 ± 2.251  ops/ms
ClientPb.getUser                         thrpt       3   9.124 ± 4.527  ops/ms
ClientPb.listUser                        thrpt       3   7.732 ± 2.503  ops/ms
ClientPb.createUser                       avgt       3   3.567 ± 1.343   ms/op
ClientPb.existUser                        avgt       3   3.321 ± 1.865   ms/op
ClientPb.getUser                          avgt       3   3.494 ± 0.693   ms/op
ClientPb.listUser                         avgt       3   4.201 ± 1.217   ms/op
ClientPb.createUser                     sample  273238   3.511 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.288           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.988           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.860           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  279345   3.437 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.998           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.140           ms/op
ClientPb.getUser                        sample  267462   3.587 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  231164   4.153 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.558           ms/op
