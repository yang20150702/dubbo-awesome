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
# Warmup Iteration   1: 1.597 ops/ms
# Warmup Iteration   2: 4.289 ops/ms
# Warmup Iteration   3: 8.297 ops/ms
Iteration   1: 8.580 ops/ms
Iteration   2: 9.105 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.922 ±(99.9%) 5.406 ops/ms [Average]
  (min, avg, max) = (8.580, 8.922, 9.105), stdev = 0.296
  CI (99.9%): [3.516, 14.329] (assumes normal distribution)


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
# Warmup Iteration   1: 2.600 ops/ms
# Warmup Iteration   2: 8.034 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 9.643 ops/ms
Iteration   2: 9.717 ops/ms
Iteration   3: 8.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.453 ±(99.9%) 7.200 ops/ms [Average]
  (min, avg, max) = (8.999, 9.453, 9.717), stdev = 0.395
  CI (99.9%): [2.253, 16.653] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 8.887 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.271 ops/ms
Iteration   3: 8.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.158 ±(99.9%) 2.954 ops/ms [Average]
  (min, avg, max) = (8.972, 9.158, 9.271), stdev = 0.162
  CI (99.9%): [6.203, 12.112] (assumes normal distribution)


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
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 6.697 ops/ms
# Warmup Iteration   3: 7.257 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.230 ops/ms
Iteration   3: 7.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.472 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (7.230, 7.472, 7.612), stdev = 0.210
  CI (99.9%): [3.641, 11.303] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.350 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.006 ms/op
Iteration   1: 3.601 ±(99.9%) 0.006 ms/op
Iteration   2: 3.602 ±(99.9%) 0.007 ms/op
Iteration   3: 3.588 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.597 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.588, 3.597, 3.602), stdev = 0.008
  CI (99.9%): [3.459, 3.735] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.597 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.005 ms/op
Iteration   2: 3.498 ±(99.9%) 0.008 ms/op
Iteration   3: 3.368 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.416 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.368, 3.416, 3.498), stdev = 0.072
  CI (99.9%): [2.103, 4.728] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.641 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.007 ms/op
Iteration   1: 3.596 ±(99.9%) 0.003 ms/op
Iteration   2: 3.506 ±(99.9%) 0.003 ms/op
Iteration   3: 3.640 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.580 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (3.506, 3.580, 3.640), stdev = 0.068
  CI (99.9%): [2.336, 4.825] (assumes normal distribution)


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
# Warmup Iteration   1: 13.080 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.006 ms/op
Iteration   1: 4.130 ±(99.9%) 0.006 ms/op
Iteration   2: 4.122 ±(99.9%) 0.010 ms/op
Iteration   3: 4.162 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.138 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (4.122, 4.138, 4.162), stdev = 0.021
  CI (99.9%): [3.751, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 12.552 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.016 ms/op
Iteration   1: 3.628 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.789 ms/op
                 createUser·p0.999:  23.003 ms/op
                 createUser·p0.9999: 30.945 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   2: 3.662 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 26.813 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.652 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.384 ms/op
                 createUser·p0.999:  26.804 ms/op
                 createUser·p0.9999: 35.548 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263060
  mean =      3.647 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3890 
    [ 2.500,  5.000) = 250000 
    [ 5.000,  7.500) = 7180 
    [ 7.500, 10.000) = 1273 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.185 ms/op
     p(99.9900) =     33.544 ms/op
     p(99.9990) =     36.593 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 9.156 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  20.185 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.427 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 24.936 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.468 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  26.120 ms/op
                 existUser·p0.9999: 44.928 ms/op
                 existUser·p1.00:   46.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279832
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 273338 
    [ 5.000, 10.000) = 5894 
    [10.000, 15.000) = 303 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 149 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     42.928 ms/op
     p(99.9990) =     45.954 ms/op
     p(99.9999) =     46.072 ms/op
    p(100.0000) =     46.072 ms/op


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
# Warmup Iteration   1: 10.949 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.012 ms/op
Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  20.999 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   2: 3.573 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  22.578 ms/op
                 getUser·p0.9999: 26.134 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 3.573 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 29.853 ms/op
                 getUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267712
  mean =      3.585 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6126 
    [ 2.500,  5.000) = 249915 
    [ 5.000,  7.500) = 9784 
    [ 7.500, 10.000) = 1275 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     27.598 ms/op
     p(99.9990) =     30.416 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 12.602 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.015 ms/op
Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 24.278 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.076 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.744 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 20.217 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.228 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.755 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231872
  mean =      4.140 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 219623 
    [ 5.000,  7.500) = 8578 
    [ 7.500, 10.000) = 2425 
    [10.000, 12.500) = 632 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     23.554 ms/op
     p(99.9990) =     25.047 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.922 ± 5.406  ops/ms
ClientPb.existUser                       thrpt       3   9.453 ± 7.200  ops/ms
ClientPb.getUser                         thrpt       3   9.158 ± 2.954  ops/ms
ClientPb.listUser                        thrpt       3   7.472 ± 3.831  ops/ms
ClientPb.createUser                       avgt       3   3.597 ± 0.138   ms/op
ClientPb.existUser                        avgt       3   3.416 ± 1.313   ms/op
ClientPb.getUser                          avgt       3   3.580 ± 1.244   ms/op
ClientPb.listUser                         avgt       3   4.138 ± 0.387   ms/op
ClientPb.createUser                     sample  263060   3.647 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.185           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.544           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  279832   3.429 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.144           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.187           ms/op
ClientPb.existUser:existUser·p0.9999    sample          42.928           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.072           ms/op
ClientPb.getUser                        sample  267712   3.585 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.228           ms/op
ClientPb.listUser                       sample  231872   4.140 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.089           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
