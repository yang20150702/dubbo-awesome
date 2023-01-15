# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.580 ops/ms
# Warmup Iteration   2: 6.258 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.827 ±(99.9%) 3.045 ops/ms [Average]
  (min, avg, max) = (9.677, 9.827, 10.007), stdev = 0.167
  CI (99.9%): [6.782, 12.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ops/ms
# Warmup Iteration   2: 9.672 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.432 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (10.325, 10.432, 10.564), stdev = 0.122
  CI (99.9%): [8.214, 12.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 9.110 ops/ms
# Warmup Iteration   3: 9.701 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 10.183 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.023 ±(99.9%) 5.095 ops/ms [Average]
  (min, avg, max) = (9.700, 10.023, 10.185), stdev = 0.279
  CI (99.9%): [4.928, 15.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.248 ops/ms
Iteration   1: 8.286 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.512 ±(99.9%) 4.011 ops/ms [Average]
  (min, avg, max) = (8.286, 8.512, 8.725), stdev = 0.220
  CI (99.9%): [4.501, 12.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.547 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.002 ms/op
Iteration   1: 3.126 ±(99.9%) 0.004 ms/op
Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
Iteration   3: 3.171 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (3.126, 3.181, 3.245), stdev = 0.060
  CI (99.9%): [2.086, 4.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.737 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.073 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.033, 3.073, 3.097), stdev = 0.035
  CI (99.9%): [2.428, 3.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.563 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.003 ms/op
Iteration   1: 3.332 ±(99.9%) 0.005 ms/op
Iteration   2: 3.220 ±(99.9%) 0.003 ms/op
Iteration   3: 3.357 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.303 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (3.220, 3.303, 3.357), stdev = 0.073
  CI (99.9%): [1.971, 4.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.022 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.006 ms/op
Iteration   1: 3.671 ±(99.9%) 0.011 ms/op
Iteration   2: 3.683 ±(99.9%) 0.011 ms/op
Iteration   3: 3.808 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (3.671, 3.720, 3.808), stdev = 0.076
  CI (99.9%): [2.335, 5.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.040 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 23.853 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.788 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  9.303 ms/op
                 createUser·p0.9999: 23.532 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  15.894 ms/op
                 createUser·p0.9999: 18.455 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298987
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24633 
    [ 2.500,  5.000) = 268223 
    [ 5.000,  7.500) = 5340 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     23.498 ms/op
     p(99.9990) =     24.380 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.159 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  8.572 ms/op
                 existUser·p0.9999: 22.055 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.527 ms/op
                 existUser·p0.9999: 26.987 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.007 ms/op
                 existUser·p0.9999: 27.613 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306961
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15268 
    [ 2.500,  5.000) = 286922 
    [ 5.000,  7.500) = 4266 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     26.716 ms/op
     p(99.9990) =     28.204 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.169 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.668 ms/op
                 getUser·p0.99:   5.435 ms/op
                 getUser·p0.999:  10.470 ms/op
                 getUser·p0.9999: 21.621 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  11.616 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 16.745 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304420
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6085 
    [ 2.500,  5.000) = 293190 
    [ 5.000,  7.500) = 4506 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     21.986 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 30.993 ms/op
                 listUser·p1.00:   31.949 ms/op

Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.353 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   3: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 15.802 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252319
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 241565 
    [ 5.000,  7.500) = 8637 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     28.813 ms/op
     p(99.9990) =     31.620 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.827 ± 3.045  ops/ms
ClientPb.existUser                       thrpt       3  10.432 ± 2.219  ops/ms
ClientPb.getUser                         thrpt       3  10.023 ± 5.095  ops/ms
ClientPb.listUser                        thrpt       3   8.512 ± 4.011  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.095   ms/op
ClientPb.existUser                        avgt       3   3.073 ± 0.646   ms/op
ClientPb.getUser                          avgt       3   3.303 ± 1.332   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 1.385   ms/op
ClientPb.createUser                     sample  298987   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.368           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.498           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  306961   3.125 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.901           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.602           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.716           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  304420   3.152 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.037           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.873           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  252319   3.800 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.949           ms/op
