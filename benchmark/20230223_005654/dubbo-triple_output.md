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
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.571 ops/ms
# Warmup Iteration   3: 7.816 ops/ms
Iteration   1: 8.052 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.282 ±(99.9%) 4.825 ops/ms [Average]
  (min, avg, max) = (8.052, 8.282, 8.571), stdev = 0.265
  CI (99.9%): [3.456, 13.107] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.504 ops/ms
# Warmup Iteration   2: 6.952 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 8.717 ops/ms
Iteration   2: 8.617 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.620 ±(99.9%) 1.745 ops/ms [Average]
  (min, avg, max) = (8.525, 8.620, 8.717), stdev = 0.096
  CI (99.9%): [6.874, 10.365] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.368 ops/ms
# Warmup Iteration   2: 6.494 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.656 ops/ms
Iteration   2: 8.559 ops/ms
Iteration   3: 8.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.670 ±(99.9%) 2.168 ops/ms [Average]
  (min, avg, max) = (8.559, 8.670, 8.796), stdev = 0.119
  CI (99.9%): [6.502, 10.839] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.256 ops/ms
# Warmup Iteration   2: 6.011 ops/ms
# Warmup Iteration   3: 7.017 ops/ms
Iteration   1: 6.955 ops/ms
Iteration   2: 7.287 ops/ms
Iteration   3: 6.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.936 ±(99.9%) 6.572 ops/ms [Average]
  (min, avg, max) = (6.567, 6.936, 7.287), stdev = 0.360
  CI (99.9%): [0.364, 13.508] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.125 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
Iteration   1: 3.965 ±(99.9%) 0.006 ms/op
Iteration   2: 4.018 ±(99.9%) 0.005 ms/op
Iteration   3: 3.801 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.928 ±(99.9%) 2.066 ms/op [Average]
  (min, avg, max) = (3.801, 3.928, 4.018), stdev = 0.113
  CI (99.9%): [1.862, 5.994] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.510 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.003 ms/op
Iteration   1: 3.931 ±(99.9%) 0.004 ms/op
Iteration   2: 3.709 ±(99.9%) 0.011 ms/op
Iteration   3: 3.544 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.728 ±(99.9%) 3.539 ms/op [Average]
  (min, avg, max) = (3.544, 3.728, 3.931), stdev = 0.194
  CI (99.9%): [0.189, 7.267] (assumes normal distribution)


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
# Warmup Iteration   1: 11.533 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.901 ±(99.9%) 0.008 ms/op
Iteration   2: 3.905 ±(99.9%) 0.009 ms/op
Iteration   3: 3.861 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.889 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (3.861, 3.889, 3.905), stdev = 0.024
  CI (99.9%): [3.443, 4.335] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.962 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.980 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.012 ms/op
Iteration   1: 4.380 ±(99.9%) 0.016 ms/op
Iteration   2: 4.673 ±(99.9%) 0.016 ms/op
Iteration   3: 4.553 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.535 ±(99.9%) 2.688 ms/op [Average]
  (min, avg, max) = (4.380, 4.535, 4.673), stdev = 0.147
  CI (99.9%): [1.848, 7.223] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.372 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 5.335 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.016 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.890 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.980 ms/op
                 createUser·p0.999:  14.339 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   2: 4.113 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  26.456 ms/op
                 createUser·p0.9999: 29.007 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  19.509 ms/op
                 createUser·p0.9999: 30.789 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240509
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 295 
    [ 2.500,  5.000) = 225476 
    [ 5.000,  7.500) = 12265 
    [ 7.500, 10.000) = 1775 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     30.081 ms/op
     p(99.9990) =     31.515 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.705 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.011 ms/op
Iteration   1: 3.662 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  9.790 ms/op
                 existUser·p0.9999: 26.518 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 27.624 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 3.802 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  27.751 ms/op
                 existUser·p0.9999: 31.660 ms/op
                 existUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254785
  mean =      3.765 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 710 
    [ 2.500,  5.000) = 246843 
    [ 5.000,  7.500) = 5788 
    [ 7.500, 10.000) = 876 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.291 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 11.796 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.013 ms/op
Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 4.080 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  24.659 ms/op
                 getUser·p0.9999: 27.104 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  15.401 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240901
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 226301 
    [ 5.000,  7.500) = 12491 
    [ 7.500, 10.000) = 1307 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     29.838 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 14.191 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.018 ms/op
Iteration   1: 4.648 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.322 ms/op
                 listUser·p0.999:  26.987 ms/op
                 listUser·p0.9999: 33.227 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 4.529 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.453 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  17.043 ms/op
                 listUser·p0.9999: 19.979 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.579 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  16.208 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209290
  mean =      4.585 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 186576 
    [ 5.000,  7.500) = 18663 
    [ 7.500, 10.000) = 2962 
    [10.000, 12.500) = 597 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     17.652 ms/op
     p(99.9900) =     32.017 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.282 ± 4.825  ops/ms
ClientPb.existUser                       thrpt       3   8.620 ± 1.745  ops/ms
ClientPb.getUser                         thrpt       3   8.670 ± 2.168  ops/ms
ClientPb.listUser                        thrpt       3   6.936 ± 6.572  ops/ms
ClientPb.createUser                       avgt       3   3.928 ± 2.066   ms/op
ClientPb.existUser                        avgt       3   3.728 ± 3.539   ms/op
ClientPb.getUser                          avgt       3   3.889 ± 0.446   ms/op
ClientPb.listUser                         avgt       3   4.535 ± 2.688   ms/op
ClientPb.createUser                     sample  240509   3.990 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.834           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.081           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.949           ms/op
ClientPb.existUser                      sample  254785   3.765 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.434           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.212           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.342           ms/op
ClientPb.getUser                        sample  240901   3.985 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.807           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.252           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.672           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  209290   4.585 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.453           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.652           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
