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
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 4.836 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.665 ops/ms
Iteration   2: 8.863 ops/ms
Iteration   3: 8.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.825 ±(99.9%) 2.639 ops/ms [Average]
  (min, avg, max) = (8.665, 8.825, 8.946), stdev = 0.145
  CI (99.9%): [6.186, 11.463] (assumes normal distribution)


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
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 8.664 ops/ms
# Warmup Iteration   3: 9.213 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 9.373 ops/ms
Iteration   3: 9.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.422 ±(99.9%) 1.038 ops/ms [Average]
  (min, avg, max) = (9.373, 9.422, 9.485), stdev = 0.057
  CI (99.9%): [8.384, 10.460] (assumes normal distribution)


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
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 8.854 ops/ms
Iteration   1: 8.566 ops/ms
Iteration   2: 9.130 ops/ms
Iteration   3: 8.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.866 ±(99.9%) 5.183 ops/ms [Average]
  (min, avg, max) = (8.566, 8.866, 9.130), stdev = 0.284
  CI (99.9%): [3.682, 14.049] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 6.791 ops/ms
# Warmup Iteration   3: 7.346 ops/ms
Iteration   1: 7.552 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.518 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (7.428, 7.518, 7.575), stdev = 0.079
  CI (99.9%): [6.071, 8.966] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.204 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.006 ms/op
Iteration   1: 3.542 ±(99.9%) 0.008 ms/op
Iteration   2: 3.566 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.529 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.481, 3.529, 3.566), stdev = 0.044
  CI (99.9%): [2.728, 4.331] (assumes normal distribution)


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
# Warmup Iteration   1: 8.720 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.003 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
Iteration   2: 3.406 ±(99.9%) 0.006 ms/op
Iteration   3: 3.422 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.419 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.406, 3.419, 3.428), stdev = 0.011
  CI (99.9%): [3.214, 3.624] (assumes normal distribution)


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
# Warmup Iteration   1: 10.547 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.006 ms/op
Iteration   1: 3.487 ±(99.9%) 0.004 ms/op
Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
Iteration   3: 3.452 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.494 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.452, 3.494, 3.543), stdev = 0.046
  CI (99.9%): [2.658, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 12.356 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.351 ±(99.9%) 0.006 ms/op
Iteration   1: 4.367 ±(99.9%) 0.009 ms/op
Iteration   2: 4.251 ±(99.9%) 0.008 ms/op
Iteration   3: 4.218 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.279 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (4.218, 4.279, 4.367), stdev = 0.078
  CI (99.9%): [2.854, 5.704] (assumes normal distribution)


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
# Warmup Iteration   1: 10.044 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.013 ms/op
Iteration   1: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  18.489 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.578 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  22.097 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.696 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  20.230 ms/op
                 createUser·p0.9999: 26.761 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267518
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3758 
    [ 2.500,  5.000) = 255487 
    [ 5.000,  7.500) = 6726 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     25.600 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 10.283 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
Iteration   1: 3.443 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  18.088 ms/op
                 existUser·p0.9999: 22.994 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.460 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  17.942 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   7.170 ms/op
                 existUser·p0.999:  22.453 ms/op
                 existUser·p0.9999: 26.131 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278160
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7245 
    [ 2.500,  5.000) = 261333 
    [ 5.000,  7.500) = 7673 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     18.864 ms/op
     p(99.9900) =     25.217 ms/op
     p(99.9990) =     26.756 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 10.408 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.012 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.740 ms/op
                 getUser·p0.999:  19.429 ms/op
                 getUser·p0.9999: 23.157 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.634 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  21.693 ms/op
                 getUser·p0.9999: 29.164 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 3.613 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  11.814 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267632
  mean =      3.586 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2335 
    [ 2.500,  5.000) = 256092 
    [ 5.000,  7.500) = 7342 
    [ 7.500, 10.000) = 1304 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     16.222 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     29.500 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 13.101 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.824 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.014 ms/op
Iteration   1: 4.397 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  20.656 ms/op
                 listUser·p0.9999: 22.658 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 4.386 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 22.385 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 4.332 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.585 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 21.405 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 219353
  mean =      4.372 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 145 
    [ 2.500,  5.000) = 204354 
    [ 5.000,  7.500) = 9974 
    [ 7.500, 10.000) = 3502 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 311 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     22.547 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.825 ± 2.639  ops/ms
ClientPb.existUser                       thrpt       3   9.422 ± 1.038  ops/ms
ClientPb.getUser                         thrpt       3   8.866 ± 5.183  ops/ms
ClientPb.listUser                        thrpt       3   7.518 ± 1.448  ops/ms
ClientPb.createUser                       avgt       3   3.529 ± 0.801   ms/op
ClientPb.existUser                        avgt       3   3.419 ± 0.205   ms/op
ClientPb.getUser                          avgt       3   3.494 ± 0.835   ms/op
ClientPb.listUser                         avgt       3   4.279 ± 1.425   ms/op
ClientPb.createUser                     sample  267518   3.587 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.600           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  278160   3.450 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.127           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  267632   3.586 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.222           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.558           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  219353   4.372 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.809           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.547           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
