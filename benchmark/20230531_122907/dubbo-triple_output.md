# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 3.561 ops/ms
# Warmup Iteration   3: 6.785 ops/ms
Iteration   1: 7.195 ops/ms
Iteration   2: 7.205 ops/ms
Iteration   3: 7.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.247 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (7.195, 7.247, 7.340), stdev = 0.081
  CI (99.9%): [5.770, 8.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 6.126 ops/ms
# Warmup Iteration   3: 7.239 ops/ms
Iteration   1: 7.695 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.708 ±(99.9%) 0.376 ops/ms [Average]
  (min, avg, max) = (7.695, 7.708, 7.731), stdev = 0.021
  CI (99.9%): [7.331, 8.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 5.691 ops/ms
# Warmup Iteration   3: 7.105 ops/ms
Iteration   1: 7.402 ops/ms
Iteration   2: 7.549 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.701 ±(99.9%) 7.268 ops/ms [Average]
  (min, avg, max) = (7.402, 7.701, 8.154), stdev = 0.398
  CI (99.9%): [0.433, 14.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.947 ops/ms
# Warmup Iteration   2: 4.878 ops/ms
# Warmup Iteration   3: 6.346 ops/ms
Iteration   1: 6.694 ops/ms
Iteration   2: 6.976 ops/ms
Iteration   3: 7.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.901 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (6.694, 6.901, 7.032), stdev = 0.181
  CI (99.9%): [3.603, 10.199] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.108 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.007 ms/op
Iteration   1: 4.160 ±(99.9%) 0.010 ms/op
Iteration   2: 4.276 ±(99.9%) 0.009 ms/op
Iteration   3: 4.208 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.215 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (4.160, 4.215, 4.276), stdev = 0.058
  CI (99.9%): [3.152, 5.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.679 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.008 ms/op
Iteration   1: 3.934 ±(99.9%) 0.009 ms/op
Iteration   2: 3.923 ±(99.9%) 0.014 ms/op
Iteration   3: 3.978 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.945 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.923, 3.945, 3.978), stdev = 0.029
  CI (99.9%): [3.412, 4.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.948 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.515 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.009 ms/op
Iteration   1: 4.148 ±(99.9%) 0.005 ms/op
Iteration   2: 4.030 ±(99.9%) 0.010 ms/op
Iteration   3: 3.929 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.036 ±(99.9%) 2.004 ms/op [Average]
  (min, avg, max) = (3.929, 4.036, 4.148), stdev = 0.110
  CI (99.9%): [2.032, 6.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.248 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.944 ±(99.9%) 0.006 ms/op
Iteration   1: 4.857 ±(99.9%) 0.013 ms/op
Iteration   2: 4.768 ±(99.9%) 0.012 ms/op
Iteration   3: 5.269 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.965 ±(99.9%) 4.879 ms/op [Average]
  (min, avg, max) = (4.768, 4.965, 5.269), stdev = 0.267
  CI (99.9%): [0.086, 9.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.933 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.401 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.471 ±(99.9%) 0.021 ms/op
Iteration   1: 3.882 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 26.854 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  15.654 ms/op
                 createUser·p0.9999: 30.387 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 3.986 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  28.173 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235922
  mean =      4.067 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 216408 
    [ 5.000,  7.500) = 16235 
    [ 7.500, 10.000) = 2126 
    [10.000, 12.500) = 513 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     24.480 ms/op
     p(99.9900) =     30.711 ms/op
     p(99.9990) =     34.032 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.699 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 4.939 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  11.227 ms/op
                 existUser·p0.9999: 26.181 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.972 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.945 ms/op
                 existUser·p0.999:  12.017 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 4.000 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  28.377 ms/op
                 existUser·p0.9999: 32.178 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240787
  mean =      3.986 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 225151 
    [ 5.000,  7.500) = 12465 
    [ 7.500, 10.000) = 2200 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     14.393 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     32.329 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.732 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.014 ms/op
Iteration   1: 4.304 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   9.568 ms/op
                 getUser·p0.999:  16.997 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   2: 4.201 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  25.715 ms/op
                 getUser·p0.9999: 31.019 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   3: 4.319 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  15.675 ms/op
                 getUser·p0.9999: 31.272 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 224682
  mean =      4.274 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 195490 
    [ 5.000,  7.500) = 23497 
    [ 7.500, 10.000) = 4004 
    [10.000, 12.500) = 1074 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.506 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     32.958 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.974 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 5.945 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.185 ±(99.9%) 0.020 ms/op
Iteration   1: 4.885 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  25.854 ms/op
                 listUser·p0.9999: 28.029 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 4.795 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  18.458 ms/op
                 listUser·p0.9999: 25.995 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.882 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  17.646 ms/op
                 listUser·p0.9999: 21.478 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197620
  mean =      4.853 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 154325 
    [ 5.000,  7.500) = 37998 
    [ 7.500, 10.000) = 4041 
    [10.000, 12.500) = 607 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      9.122 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.345 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.247 ± 1.477  ops/ms
ClientPb.existUser                       thrpt       3   7.708 ± 0.376  ops/ms
ClientPb.getUser                         thrpt       3   7.701 ± 7.268  ops/ms
ClientPb.listUser                        thrpt       3   6.901 ± 3.298  ops/ms
ClientPb.createUser                       avgt       3   4.215 ± 1.063   ms/op
ClientPb.existUser                        avgt       3   3.945 ± 0.533   ms/op
ClientPb.getUser                          avgt       3   4.036 ± 2.004   ms/op
ClientPb.listUser                         avgt       3   4.965 ± 4.879   ms/op
ClientPb.createUser                     sample  235922   4.067 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.632           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.711           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  240787   3.986 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.501           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.393           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  224682   4.274 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.606           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.224           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.506           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.900           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  197620   4.853 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.122           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.349           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.197           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
