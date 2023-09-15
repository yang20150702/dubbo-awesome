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
# Warmup Iteration   1: 1.473 ops/ms
# Warmup Iteration   2: 3.608 ops/ms
# Warmup Iteration   3: 7.235 ops/ms
Iteration   1: 7.294 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 7.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.793 ±(99.9%) 7.918 ops/ms [Average]
  (min, avg, max) = (7.294, 7.793, 8.087), stdev = 0.434
  CI (99.9%): [≈ 0, 15.711] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 7.150 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 8.226 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.323 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (8.226, 8.323, 8.399), stdev = 0.088
  CI (99.9%): [6.710, 9.935] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 6.782 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.994 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.027 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (7.978, 8.027, 8.108), stdev = 0.071
  CI (99.9%): [6.735, 9.318] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.135 ops/ms
# Warmup Iteration   2: 5.988 ops/ms
# Warmup Iteration   3: 6.635 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.841 ops/ms
Iteration   3: 6.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.726 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (6.624, 6.726, 6.841), stdev = 0.109
  CI (99.9%): [4.742, 8.711] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.148 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.006 ms/op
Iteration   1: 4.069 ±(99.9%) 0.007 ms/op
Iteration   2: 4.221 ±(99.9%) 0.007 ms/op
Iteration   3: 3.967 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.086 ±(99.9%) 2.326 ms/op [Average]
  (min, avg, max) = (3.967, 4.086, 4.221), stdev = 0.127
  CI (99.9%): [1.760, 6.411] (assumes normal distribution)


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
# Warmup Iteration   1: 12.179 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.002 ms/op
Iteration   1: 3.886 ±(99.9%) 0.003 ms/op
Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
Iteration   3: 3.925 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.870 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.798, 3.870, 3.925), stdev = 0.065
  CI (99.9%): [2.683, 5.057] (assumes normal distribution)


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
# Warmup Iteration   1: 12.502 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.002 ms/op
Iteration   1: 4.082 ±(99.9%) 0.004 ms/op
Iteration   2: 3.938 ±(99.9%) 0.005 ms/op
Iteration   3: 3.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.985 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.935, 3.985, 4.082), stdev = 0.084
  CI (99.9%): [2.454, 5.516] (assumes normal distribution)


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
# Warmup Iteration   1: 13.864 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.006 ms/op
Iteration   1: 4.903 ±(99.9%) 0.007 ms/op
Iteration   2: 4.897 ±(99.9%) 0.005 ms/op
Iteration   3: 4.838 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.879 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (4.838, 4.879, 4.903), stdev = 0.036
  CI (99.9%): [4.218, 5.541] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.819 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.017 ms/op
Iteration   1: 4.020 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  23.443 ms/op
                 createUser·p0.9999: 44.111 ms/op
                 createUser·p1.00:   45.285 ms/op

Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.609 ms/op
                 createUser·p0.999:  25.035 ms/op
                 createUser·p0.9999: 27.040 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  17.328 ms/op
                 createUser·p0.9999: 31.710 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240196
  mean =      3.994 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 227767 
    [ 5.000, 10.000) = 11673 
    [10.000, 15.000) = 403 
    [15.000, 20.000) = 79 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 131 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     23.881 ms/op
     p(99.9900) =     40.689 ms/op
     p(99.9990) =     45.180 ms/op
     p(99.9999) =     45.285 ms/op
    p(100.0000) =     45.285 ms/op


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
# Warmup Iteration   1: 11.625 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 22.892 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.600 ms/op
                 existUser·p0.999:  15.204 ms/op
                 existUser·p0.9999: 24.080 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  16.008 ms/op
                 existUser·p0.9999: 27.191 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244576
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 294 
    [ 2.500,  5.000) = 233863 
    [ 5.000,  7.500) = 8007 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     26.363 ms/op
     p(99.9990) =     28.075 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 12.126 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.016 ms/op
Iteration   1: 4.134 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.847 ms/op
                 getUser·p0.999:  23.909 ms/op
                 getUser·p0.9999: 26.094 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.971 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 26.573 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.968 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  26.543 ms/op
                 getUser·p0.9999: 31.058 ms/op
                 getUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238546
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 227300 
    [ 5.000,  7.500) = 7762 
    [ 7.500, 10.000) = 2572 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     23.837 ms/op
     p(99.9900) =     30.222 ms/op
     p(99.9990) =     31.248 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.375 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.793 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.016 ms/op
Iteration   1: 4.801 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  24.885 ms/op
                 listUser·p0.9999: 29.711 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 4.753 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  18.406 ms/op
                 listUser·p0.9999: 20.909 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.940 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.461 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 17.893 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198618
  mean =      4.830 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 151388 
    [ 5.000,  7.500) = 42632 
    [ 7.500, 10.000) = 3652 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 223 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     28.625 ms/op
     p(99.9990) =     30.573 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.793 ± 7.918  ops/ms
ClientPb.existUser                       thrpt       3   8.323 ± 1.613  ops/ms
ClientPb.getUser                         thrpt       3   8.027 ± 1.292  ops/ms
ClientPb.listUser                        thrpt       3   6.726 ± 1.984  ops/ms
ClientPb.createUser                       avgt       3   4.086 ± 2.326   ms/op
ClientPb.existUser                        avgt       3   3.870 ± 1.187   ms/op
ClientPb.getUser                          avgt       3   3.985 ± 1.531   ms/op
ClientPb.listUser                         avgt       3   4.879 ± 0.661   ms/op
ClientPb.createUser                     sample  240196   3.994 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.348           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.881           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.689           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.285           ms/op
ClientPb.existUser                      sample  244576   3.926 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.479           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.363           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  238546   4.023 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.036           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.837           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.222           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.425           ms/op
ClientPb.listUser                       sample  198618   4.830 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.655           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.743           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.625           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
