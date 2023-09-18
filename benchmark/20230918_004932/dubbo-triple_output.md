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
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 5.885 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 9.190 ops/ms
Iteration   2: 9.200 ops/ms
Iteration   3: 9.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.200 ±(99.9%) 0.196 ops/ms [Average]
  (min, avg, max) = (9.190, 9.200, 9.211), stdev = 0.011
  CI (99.9%): [9.004, 9.396] (assumes normal distribution)


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
# Warmup Iteration   1: 2.732 ops/ms
# Warmup Iteration   2: 8.639 ops/ms
# Warmup Iteration   3: 9.631 ops/ms
Iteration   1: 9.722 ops/ms
Iteration   2: 9.828 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.768 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (9.722, 9.768, 9.828), stdev = 0.054
  CI (99.9%): [8.781, 10.756] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ops/ms
# Warmup Iteration   2: 8.841 ops/ms
# Warmup Iteration   3: 8.822 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.346 ops/ms
Iteration   3: 9.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.333 ±(99.9%) 2.974 ops/ms [Average]
  (min, avg, max) = (9.164, 9.333, 9.490), stdev = 0.163
  CI (99.9%): [6.360, 12.307] (assumes normal distribution)


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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.943 ops/ms
# Warmup Iteration   3: 7.368 ops/ms
Iteration   1: 7.724 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.792 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (7.724, 7.792, 7.829), stdev = 0.059
  CI (99.9%): [6.710, 8.875] (assumes normal distribution)


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
# Warmup Iteration   1: 9.699 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.004 ms/op
Iteration   1: 3.500 ±(99.9%) 0.008 ms/op
Iteration   2: 3.441 ±(99.9%) 0.006 ms/op
Iteration   3: 3.458 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.466 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.441, 3.466, 3.500), stdev = 0.030
  CI (99.9%): [2.914, 4.019] (assumes normal distribution)


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
# Warmup Iteration   1: 7.880 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.004 ms/op
Iteration   1: 3.273 ±(99.9%) 0.004 ms/op
Iteration   2: 3.268 ±(99.9%) 0.005 ms/op
Iteration   3: 3.360 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.300 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.268, 3.300, 3.360), stdev = 0.052
  CI (99.9%): [2.350, 4.251] (assumes normal distribution)


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
# Warmup Iteration   1: 8.460 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.003 ms/op
Iteration   1: 3.496 ±(99.9%) 0.003 ms/op
Iteration   2: 3.455 ±(99.9%) 0.004 ms/op
Iteration   3: 3.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.464 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.441, 3.464, 3.496), stdev = 0.029
  CI (99.9%): [2.939, 3.989] (assumes normal distribution)


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
# Warmup Iteration   1: 10.033 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.009 ms/op
Iteration   1: 4.244 ±(99.9%) 0.010 ms/op
Iteration   2: 4.188 ±(99.9%) 0.004 ms/op
Iteration   3: 4.165 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.199 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (4.165, 4.199, 4.244), stdev = 0.041
  CI (99.9%): [3.453, 4.945] (assumes normal distribution)


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
# Warmup Iteration   1: 10.447 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.013 ms/op
Iteration   1: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  21.596 ms/op
                 createUser·p0.9999: 23.911 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.445 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.733 ms/op
                 createUser·p0.999:  21.869 ms/op
                 createUser·p0.9999: 26.168 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.797 ms/op
                 createUser·p0.9999: 29.291 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278007
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3795 
    [ 2.500,  5.000) = 269239 
    [ 5.000,  7.500) = 3938 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     28.318 ms/op
     p(99.9990) =     29.801 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  10.615 ms/op
                 existUser·p0.9999: 21.311 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 23.562 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  18.309 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287706
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12705 
    [ 2.500,  5.000) = 270390 
    [ 5.000,  7.500) = 3635 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     25.239 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 9.547 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
Iteration   1: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  20.901 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  21.767 ms/op
                 getUser·p0.9999: 24.987 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.383 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  18.307 ms/op
                 getUser·p0.9999: 24.233 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280385
  mean =      3.423 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3860 
    [ 2.500,  5.000) = 271063 
    [ 5.000,  7.500) = 4558 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     18.594 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     25.421 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 10.169 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.011 ms/op
Iteration   1: 4.205 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 21.423 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 4.136 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 17.900 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.122 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230946
  mean =      4.154 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 222378 
    [ 5.000,  7.500) = 6308 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     20.182 ms/op
     p(99.9990) =     21.748 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.200 ± 0.196  ops/ms
ClientPb.existUser                       thrpt       3   9.768 ± 0.988  ops/ms
ClientPb.getUser                         thrpt       3   9.333 ± 2.974  ops/ms
ClientPb.listUser                        thrpt       3   7.792 ± 1.082  ops/ms
ClientPb.createUser                       avgt       3   3.466 ± 0.553   ms/op
ClientPb.existUser                        avgt       3   3.300 ± 0.951   ms/op
ClientPb.getUser                          avgt       3   3.464 ± 0.525   ms/op
ClientPb.listUser                         avgt       3   4.199 ± 0.746   ms/op
ClientPb.createUser                     sample  278007   3.452 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.756           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.414           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.318           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  287706   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.239           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.591           ms/op
ClientPb.getUser                        sample  280385   3.423 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.314           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  230946   4.154 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.432           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.253           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.182           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.544           ms/op
