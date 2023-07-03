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
# Warmup Iteration   1: 1.369 ops/ms
# Warmup Iteration   2: 3.971 ops/ms
# Warmup Iteration   3: 6.287 ops/ms
Iteration   1: 6.261 ops/ms
Iteration   2: 6.917 ops/ms
Iteration   3: 7.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.769 ±(99.9%) 8.245 ops/ms [Average]
  (min, avg, max) = (6.261, 6.769, 7.128), stdev = 0.452
  CI (99.9%): [≈ 0, 15.013] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 5.891 ops/ms
# Warmup Iteration   3: 6.822 ops/ms
Iteration   1: 7.115 ops/ms
Iteration   2: 7.557 ops/ms
Iteration   3: 7.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.238 ±(99.9%) 5.072 ops/ms [Average]
  (min, avg, max) = (7.043, 7.238, 7.557), stdev = 0.278
  CI (99.9%): [2.166, 12.310] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 5.387 ops/ms
# Warmup Iteration   3: 6.590 ops/ms
Iteration   1: 6.670 ops/ms
Iteration   2: 6.362 ops/ms
Iteration   3: 6.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.482 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (6.362, 6.482, 6.670), stdev = 0.165
  CI (99.9%): [3.476, 9.487] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.755 ops/ms
# Warmup Iteration   2: 5.033 ops/ms
# Warmup Iteration   3: 5.754 ops/ms
Iteration   1: 5.903 ops/ms
Iteration   2: 5.817 ops/ms
Iteration   3: 5.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.902 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (5.817, 5.902, 5.986), stdev = 0.085
  CI (99.9%): [4.355, 7.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.720 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.645 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.985 ±(99.9%) 0.005 ms/op
Iteration   1: 4.773 ±(99.9%) 0.011 ms/op
Iteration   2: 4.677 ±(99.9%) 0.015 ms/op
Iteration   3: 4.809 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.753 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (4.677, 4.753, 4.809), stdev = 0.068
  CI (99.9%): [3.506, 6.000] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.695 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.012 ms/op
Iteration   1: 4.580 ±(99.9%) 0.011 ms/op
Iteration   2: 4.545 ±(99.9%) 0.012 ms/op
Iteration   3: 4.481 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.535 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (4.481, 4.535, 4.580), stdev = 0.051
  CI (99.9%): [3.614, 5.457] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.573 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.289 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.644 ±(99.9%) 0.017 ms/op
Iteration   1: 4.751 ±(99.9%) 0.010 ms/op
Iteration   2: 4.638 ±(99.9%) 0.009 ms/op
Iteration   3: 4.658 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.682 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (4.638, 4.682, 4.751), stdev = 0.061
  CI (99.9%): [3.577, 5.788] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.674 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.360 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.009 ms/op
Iteration   1: 5.747 ±(99.9%) 0.012 ms/op
Iteration   2: 5.547 ±(99.9%) 0.014 ms/op
Iteration   3: 5.564 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.619 ±(99.9%) 2.018 ms/op [Average]
  (min, avg, max) = (5.547, 5.619, 5.747), stdev = 0.111
  CI (99.9%): [3.602, 7.637] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.545 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.412 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.081 ±(99.9%) 0.021 ms/op
Iteration   1: 4.846 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   6.246 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  18.876 ms/op
                 createUser·p0.9999: 23.272 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 4.519 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  14.044 ms/op
                 createUser·p0.9999: 26.335 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 4.453 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  25.907 ms/op
                 createUser·p0.9999: 33.215 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 208646
  mean =      4.600 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 163002 
    [ 5.000,  7.500) = 39807 
    [ 7.500, 10.000) = 4349 
    [10.000, 12.500) = 759 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     21.606 ms/op
     p(99.9900) =     32.248 ms/op
     p(99.9990) =     34.073 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.753 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.018 ms/op
Iteration   1: 4.606 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.898 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.943 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 4.601 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   8.519 ms/op
                 existUser·p0.999:  14.131 ms/op
                 existUser·p0.9999: 28.842 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   3: 4.652 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.742 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 33.664 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 207587
  mean =      4.619 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182 
    [ 2.500,  5.000) = 160871 
    [ 5.000,  7.500) = 41590 
    [ 7.500, 10.000) = 4026 
    [10.000, 12.500) = 605 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     33.160 ms/op
     p(99.9990) =     34.467 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 13.180 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.377 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.918 ±(99.9%) 0.018 ms/op
Iteration   1: 4.808 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.463 ms/op
                 getUser·p0.99:   11.436 ms/op
                 getUser·p0.999:  22.448 ms/op
                 getUser·p0.9999: 26.696 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 4.677 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   4.448 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.429 ms/op
                 getUser·p0.99:   8.591 ms/op
                 getUser·p0.999:  16.181 ms/op
                 getUser·p0.9999: 26.179 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 4.715 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.750 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  26.140 ms/op
                 getUser·p0.9999: 38.666 ms/op
                 getUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 202744
  mean =      4.733 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 152243 
    [ 5.000,  7.500) = 43780 
    [ 7.500, 10.000) = 4888 
    [10.000, 12.500) = 1059 
    [12.500, 15.000) = 354 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     37.272 ms/op
     p(99.9990) =     39.189 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 16.356 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.447 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.022 ms/op
Iteration   1: 5.340 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.286 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  24.220 ms/op
                 listUser·p0.9999: 34.406 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   2: 5.319 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 31.195 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   3: 5.324 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.795 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 22.731 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 180085
  mean =      5.328 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 82201 
    [ 5.000,  7.500) = 90391 
    [ 7.500, 10.000) = 5806 
    [10.000, 12.500) = 1038 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     21.755 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     34.695 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.769 ± 8.245  ops/ms
ClientPb.existUser                       thrpt       3   7.238 ± 5.072  ops/ms
ClientPb.getUser                         thrpt       3   6.482 ± 3.005  ops/ms
ClientPb.listUser                        thrpt       3   5.902 ± 1.547  ops/ms
ClientPb.createUser                       avgt       3   4.753 ± 1.247   ms/op
ClientPb.existUser                        avgt       3   4.535 ± 0.921   ms/op
ClientPb.getUser                          avgt       3   4.682 ± 1.106   ms/op
ClientPb.listUser                         avgt       3   5.619 ± 2.018   ms/op
ClientPb.createUser                     sample  208646   4.600 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.817           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.946           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.606           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  207587   4.619 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.898           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.798           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.160           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  202744   4.733 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.090           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.634           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.429           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.272           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  180085   5.328 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.896           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.755           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.489           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
