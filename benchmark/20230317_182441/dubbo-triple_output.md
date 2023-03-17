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
# Warmup Iteration   1: 1.675 ops/ms
# Warmup Iteration   2: 3.546 ops/ms
# Warmup Iteration   3: 7.099 ops/ms
Iteration   1: 7.086 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.768 ±(99.9%) 11.229 ops/ms [Average]
  (min, avg, max) = (7.086, 7.768, 8.282), stdev = 0.615
  CI (99.9%): [≈ 0, 18.996] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.277 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 7.969 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.646 ops/ms
Iteration   3: 8.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.517 ±(99.9%) 3.652 ops/ms [Average]
  (min, avg, max) = (8.287, 8.517, 8.646), stdev = 0.200
  CI (99.9%): [4.865, 12.170] (assumes normal distribution)


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
# Warmup Iteration   1: 2.056 ops/ms
# Warmup Iteration   2: 6.251 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 7.930 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.034 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (7.930, 8.034, 8.136), stdev = 0.103
  CI (99.9%): [6.159, 9.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.022 ops/ms
# Warmup Iteration   3: 6.761 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.737 ops/ms
Iteration   3: 7.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.729 ±(99.9%) 5.359 ops/ms [Average]
  (min, avg, max) = (6.431, 6.729, 7.018), stdev = 0.294
  CI (99.9%): [1.370, 12.088] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.688 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.006 ms/op
Iteration   1: 3.987 ±(99.9%) 0.004 ms/op
Iteration   2: 4.070 ±(99.9%) 0.009 ms/op
Iteration   3: 3.909 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.988 ±(99.9%) 1.468 ms/op [Average]
  (min, avg, max) = (3.909, 3.988, 4.070), stdev = 0.080
  CI (99.9%): [2.520, 5.457] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.841 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.009 ms/op
Iteration   1: 3.821 ±(99.9%) 0.007 ms/op
Iteration   2: 3.681 ±(99.9%) 0.007 ms/op
Iteration   3: 3.755 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.752 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.681, 3.752, 3.821), stdev = 0.070
  CI (99.9%): [2.473, 5.032] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.223 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
Iteration   2: 3.809 ±(99.9%) 0.010 ms/op
Iteration   3: 3.851 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.886 ±(99.9%) 1.816 ms/op [Average]
  (min, avg, max) = (3.809, 3.886, 3.998), stdev = 0.100
  CI (99.9%): [2.070, 5.702] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.561 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.455 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.885 ±(99.9%) 0.008 ms/op
Iteration   1: 4.927 ±(99.9%) 0.008 ms/op
Iteration   2: 4.706 ±(99.9%) 0.012 ms/op
Iteration   3: 4.540 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.724 ±(99.9%) 3.547 ms/op [Average]
  (min, avg, max) = (4.540, 4.724, 4.927), stdev = 0.194
  CI (99.9%): [1.177, 8.271] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.540 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.198 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.611 ±(99.9%) 0.019 ms/op
Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  22.996 ms/op
                 createUser·p0.9999: 28.110 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  24.871 ms/op
                 createUser·p0.9999: 27.559 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 27.976 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241598
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 532 
    [ 2.500,  5.000) = 228211 
    [ 5.000,  7.500) = 10856 
    [ 7.500, 10.000) = 1332 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 149 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     27.913 ms/op
     p(99.9990) =     28.789 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 12.786 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.013 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  14.172 ms/op
                 existUser·p0.9999: 27.084 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 3.779 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.533 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  26.247 ms/op
                 existUser·p0.9999: 30.361 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 3.816 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.989 ms/op
                 existUser·p0.999:  13.642 ms/op
                 existUser·p0.9999: 33.624 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248796
  mean =      3.856 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 238083 
    [ 5.000,  7.500) = 7915 
    [ 7.500, 10.000) = 1742 
    [10.000, 12.500) = 459 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     14.569 ms/op
     p(99.9900) =     32.304 ms/op
     p(99.9990) =     34.047 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.834 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.735 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.015 ms/op
Iteration   1: 4.060 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  19.726 ms/op
                 getUser·p0.9999: 26.776 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 27.615 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   3: 3.867 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.032 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  14.740 ms/op
                 getUser·p0.9999: 31.387 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243862
  mean =      3.933 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 148 
    [ 2.500,  5.000) = 231377 
    [ 5.000,  7.500) = 9822 
    [ 7.500, 10.000) = 1866 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     20.321 ms/op
     p(99.9900) =     29.879 ms/op
     p(99.9990) =     31.848 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 13.601 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.869 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.010 ±(99.9%) 0.019 ms/op
Iteration   1: 4.730 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.968 ms/op
                 listUser·p0.999:  26.083 ms/op
                 listUser·p0.9999: 28.581 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   2: 4.717 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.957 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  18.619 ms/op
                 listUser·p0.9999: 23.207 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.884 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 22.771 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200820
  mean =      4.776 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 163972 
    [ 5.000,  7.500) = 31803 
    [ 7.500, 10.000) = 3565 
    [10.000, 12.500) = 863 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     21.829 ms/op
     p(99.9900) =     27.976 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.768 ± 11.229  ops/ms
ClientPb.existUser                       thrpt       3   8.517 ±  3.652  ops/ms
ClientPb.getUser                         thrpt       3   8.034 ±  1.876  ops/ms
ClientPb.listUser                        thrpt       3   6.729 ±  5.359  ops/ms
ClientPb.createUser                       avgt       3   3.988 ±  1.468   ms/op
ClientPb.existUser                        avgt       3   3.752 ±  1.279   ms/op
ClientPb.getUser                          avgt       3   3.886 ±  1.816   ms/op
ClientPb.listUser                         avgt       3   4.724 ±  3.547   ms/op
ClientPb.createUser                     sample  241598   3.972 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.440            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.079            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.258            ms/op
ClientPb.createUser:createUser·p0.999   sample          22.938            ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.913            ms/op
ClientPb.createUser:createUser·p1.00    sample          29.229            ms/op
ClientPb.existUser                      sample  248796   3.856 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.636            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.817            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.553            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.569            ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.304            ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258            ms/op
ClientPb.getUser                        sample  243862   3.933 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.587            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.777            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.586            ms/op
ClientPb.getUser:getUser·p0.999         sample          20.321            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.879            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.113            ms/op
ClientPb.listUser                       sample  200820   4.776 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.396            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.972            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.829            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.976            ms/op
ClientPb.listUser:listUser·p1.00        sample          29.032            ms/op
