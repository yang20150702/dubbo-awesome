# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.706 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 7.567 ops/ms
Iteration   1: 7.685 ops/ms
Iteration   2: 8.360 ops/ms
Iteration   3: 8.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.133 ±(99.9%) 7.071 ops/ms [Average]
  (min, avg, max) = (7.685, 8.133, 8.360), stdev = 0.388
  CI (99.9%): [1.062, 15.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 7.410 ops/ms
# Warmup Iteration   3: 8.162 ops/ms
Iteration   1: 8.379 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.493 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (8.379, 8.493, 8.626), stdev = 0.125
  CI (99.9%): [6.215, 10.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 6.718 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 8.028 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.047 ±(99.9%) 4.486 ops/ms [Average]
  (min, avg, max) = (7.811, 8.047, 8.301), stdev = 0.246
  CI (99.9%): [3.560, 12.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.989 ops/ms
# Warmup Iteration   2: 5.344 ops/ms
# Warmup Iteration   3: 6.646 ops/ms
Iteration   1: 7.063 ops/ms
Iteration   2: 6.957 ops/ms
Iteration   3: 7.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.006 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (6.957, 7.006, 7.063), stdev = 0.053
  CI (99.9%): [6.032, 7.980] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.815 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.739 ±(99.9%) 0.014 ms/op
Iteration   2: 3.800 ±(99.9%) 0.010 ms/op
Iteration   3: 3.886 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.808 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (3.739, 3.808, 3.886), stdev = 0.074
  CI (99.9%): [2.460, 5.156] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.004 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.004 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
Iteration   2: 3.661 ±(99.9%) 0.006 ms/op
Iteration   3: 3.661 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.685 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.661, 3.685, 3.734), stdev = 0.042
  CI (99.9%): [2.924, 4.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.627 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
Iteration   2: 3.878 ±(99.9%) 0.007 ms/op
Iteration   3: 3.821 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.875 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.821, 3.875, 3.926), stdev = 0.053
  CI (99.9%): [2.915, 4.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.477 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.006 ms/op
Iteration   1: 4.497 ±(99.9%) 0.010 ms/op
Iteration   2: 4.480 ±(99.9%) 0.009 ms/op
Iteration   3: 4.421 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.466 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (4.421, 4.466, 4.497), stdev = 0.040
  CI (99.9%): [3.745, 5.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.494 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.016 ms/op
Iteration   1: 3.938 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  24.090 ms/op
                 createUser·p0.9999: 29.684 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  25.435 ms/op
                 createUser·p0.9999: 28.237 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 34.918 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244532
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 897 
    [ 2.500,  5.000) = 231595 
    [ 5.000,  7.500) = 10408 
    [ 7.500, 10.000) = 1192 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     32.443 ms/op
     p(99.9990) =     35.229 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.376 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.893 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 28.087 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 3.627 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.208 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  24.468 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  17.671 ms/op
                 existUser·p0.9999: 30.147 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256886
  mean =      3.738 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1090 
    [ 2.500,  5.000) = 246091 
    [ 5.000,  7.500) = 8329 
    [ 7.500, 10.000) = 876 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     29.272 ms/op
     p(99.9990) =     30.456 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.519 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.017 ms/op
Iteration   1: 3.989 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  23.460 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.539 ms/op
                 getUser·p0.999:  25.100 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.764 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  11.992 ms/op
                 getUser·p0.9999: 31.096 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 248095
  mean =      3.868 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 361 
    [ 2.500,  5.000) = 236748 
    [ 5.000,  7.500) = 8814 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     23.187 ms/op
     p(99.9900) =     30.186 ms/op
     p(99.9990) =     31.575 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.186 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.016 ms/op
Iteration   1: 4.696 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.865 ms/op
                 listUser·p0.999:  22.571 ms/op
                 listUser·p0.9999: 26.155 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 4.644 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 20.582 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.665 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.855 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205535
  mean =      4.668 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 174224 
    [ 5.000,  7.500) = 27255 
    [ 7.500, 10.000) = 2998 
    [10.000, 12.500) = 567 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      8.825 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     26.537 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.133 ± 7.071  ops/ms
ClientPb.existUser                       thrpt       3   8.493 ± 2.278  ops/ms
ClientPb.getUser                         thrpt       3   8.047 ± 4.486  ops/ms
ClientPb.listUser                        thrpt       3   7.006 ± 0.974  ops/ms
ClientPb.createUser                       avgt       3   3.808 ± 1.348   ms/op
ClientPb.existUser                        avgt       3   3.685 ± 0.761   ms/op
ClientPb.getUser                          avgt       3   3.875 ± 0.960   ms/op
ClientPb.listUser                         avgt       3   4.466 ± 0.721   ms/op
ClientPb.createUser                     sample  244532   3.923 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.443           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  256886   3.738 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.272           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  248095   3.868 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.420           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.299           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.187           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.186           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  205535   4.668 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.825           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.347           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
