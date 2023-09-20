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
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.125 ops/ms
Iteration   3: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.276 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (9.125, 9.276, 9.411), stdev = 0.143
  CI (99.9%): [6.660, 11.892] (assumes normal distribution)


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
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 8.787 ops/ms
# Warmup Iteration   3: 9.729 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.732 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (9.540, 9.732, 9.866), stdev = 0.170
  CI (99.9%): [6.629, 12.834] (assumes normal distribution)


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
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 8.676 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.472 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.307 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (9.223, 9.307, 9.472), stdev = 0.144
  CI (99.9%): [6.688, 11.925] (assumes normal distribution)


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
# Warmup Iteration   1: 2.991 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.558 ops/ms
Iteration   1: 7.871 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 7.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.846 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (7.789, 7.846, 7.879), stdev = 0.050
  CI (99.9%): [6.942, 8.751] (assumes normal distribution)


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
# Warmup Iteration   1: 10.678 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.003 ms/op
Iteration   1: 3.522 ±(99.9%) 0.005 ms/op
Iteration   2: 3.478 ±(99.9%) 0.005 ms/op
Iteration   3: 3.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.476 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.429, 3.476, 3.522), stdev = 0.047
  CI (99.9%): [2.625, 4.328] (assumes normal distribution)


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
# Warmup Iteration   1: 9.670 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.006 ms/op
Iteration   1: 3.287 ±(99.9%) 0.005 ms/op
Iteration   2: 3.302 ±(99.9%) 0.005 ms/op
Iteration   3: 3.218 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.269 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.218, 3.269, 3.302), stdev = 0.045
  CI (99.9%): [2.455, 4.084] (assumes normal distribution)


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
# Warmup Iteration   1: 9.072 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.003 ms/op
Iteration   1: 3.551 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.005 ms/op
Iteration   3: 3.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.493 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.446, 3.493, 3.551), stdev = 0.053
  CI (99.9%): [2.530, 4.457] (assumes normal distribution)


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
# Warmup Iteration   1: 9.700 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.006 ms/op
Iteration   1: 4.079 ±(99.9%) 0.005 ms/op
Iteration   2: 4.098 ±(99.9%) 0.005 ms/op
Iteration   3: 4.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.082 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (4.070, 4.082, 4.098), stdev = 0.015
  CI (99.9%): [3.817, 4.348] (assumes normal distribution)


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
# Warmup Iteration   1: 8.119 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
Iteration   1: 3.441 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  16.581 ms/op
                 createUser·p0.9999: 18.177 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 3.423 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 19.933 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 31.350 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279243
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12078 
    [ 2.500,  5.000) = 261925 
    [ 5.000,  7.500) = 4080 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     17.294 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     31.497 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 7.223 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.007 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  16.835 ms/op
                 existUser·p0.9999: 23.610 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.697 ms/op
                 existUser·p0.999:  12.929 ms/op
                 existUser·p0.9999: 24.583 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  16.277 ms/op
                 existUser·p0.9999: 28.541 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289625
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3479 
    [ 2.500,  5.000) = 281433 
    [ 5.000,  7.500) = 3677 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     13.007 ms/op
     p(99.9900) =     27.496 ms/op
     p(99.9990) =     28.777 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 8.971 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
Iteration   1: 3.577 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  18.694 ms/op
                 getUser·p0.9999: 22.654 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  22.087 ms/op
                 getUser·p0.9999: 24.845 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 27.787 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273439
  mean =      3.507 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3858 
    [ 2.500,  5.000) = 262881 
    [ 5.000,  7.500) = 5612 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     26.498 ms/op
     p(99.9990) =     28.165 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.764 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.011 ms/op
Iteration   1: 4.004 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.730 ms/op
                 listUser·p0.9999: 20.615 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 4.046 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.432 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 3.977 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239336
  mean =      4.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 230738 
    [ 5.000,  7.500) = 7007 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     19.630 ms/op
     p(99.9990) =     21.300 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.276 ± 2.616  ops/ms
ClientPb.existUser                       thrpt       3   9.732 ± 3.102  ops/ms
ClientPb.getUser                         thrpt       3   9.307 ± 2.618  ops/ms
ClientPb.listUser                        thrpt       3   7.846 ± 0.905  ops/ms
ClientPb.createUser                       avgt       3   3.476 ± 0.852   ms/op
ClientPb.existUser                        avgt       3   3.269 ± 0.814   ms/op
ClientPb.getUser                          avgt       3   3.493 ± 0.964   ms/op
ClientPb.listUser                         avgt       3   4.082 ± 0.266   ms/op
ClientPb.createUser                     sample  279243   3.435 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.401           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.294           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.900           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  289625   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.007           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  273439   3.507 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.012           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.579           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.279           ms/op
ClientPb.listUser                       sample  239336   4.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.374           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.630           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
