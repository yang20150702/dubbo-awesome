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
# Warmup Iteration   1: 1.796 ops/ms
# Warmup Iteration   2: 3.738 ops/ms
# Warmup Iteration   3: 7.007 ops/ms
Iteration   1: 7.684 ops/ms
Iteration   2: 8.273 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.988 ±(99.9%) 5.376 ops/ms [Average]
  (min, avg, max) = (7.684, 7.988, 8.273), stdev = 0.295
  CI (99.9%): [2.612, 13.364] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.315 ops/ms
# Warmup Iteration   2: 6.967 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 8.823 ops/ms
Iteration   2: 8.514 ops/ms
Iteration   3: 8.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.693 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (8.514, 8.693, 8.823), stdev = 0.160
  CI (99.9%): [5.766, 11.620] (assumes normal distribution)


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
# Warmup Iteration   1: 2.034 ops/ms
# Warmup Iteration   2: 6.367 ops/ms
# Warmup Iteration   3: 7.878 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.615 ops/ms
Iteration   3: 8.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.519 ±(99.9%) 4.154 ops/ms [Average]
  (min, avg, max) = (8.259, 8.519, 8.682), stdev = 0.228
  CI (99.9%): [4.364, 12.673] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.400 ops/ms
# Warmup Iteration   2: 6.005 ops/ms
# Warmup Iteration   3: 6.634 ops/ms
Iteration   1: 7.073 ops/ms
Iteration   2: 7.464 ops/ms
Iteration   3: 7.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.452 ±(99.9%) 6.802 ops/ms [Average]
  (min, avg, max) = (7.073, 7.452, 7.818), stdev = 0.373
  CI (99.9%): [0.650, 14.253] (assumes normal distribution)


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
# Warmup Iteration   1: 11.693 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.005 ms/op
Iteration   1: 3.805 ±(99.9%) 0.013 ms/op
Iteration   2: 3.890 ±(99.9%) 0.008 ms/op
Iteration   3: 3.986 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.894 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.805, 3.894, 3.986), stdev = 0.091
  CI (99.9%): [2.243, 5.545] (assumes normal distribution)


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
# Warmup Iteration   1: 12.555 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.005 ms/op
Iteration   1: 3.536 ±(99.9%) 0.006 ms/op
Iteration   2: 3.543 ±(99.9%) 0.007 ms/op
Iteration   3: 3.588 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.555 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.536, 3.555, 3.588), stdev = 0.028
  CI (99.9%): [3.044, 4.067] (assumes normal distribution)


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
# Warmup Iteration   1: 11.722 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.007 ms/op
Iteration   1: 3.913 ±(99.9%) 0.005 ms/op
Iteration   2: 3.984 ±(99.9%) 0.007 ms/op
Iteration   3: 3.839 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.912 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.839, 3.912, 3.984), stdev = 0.072
  CI (99.9%): [2.589, 5.234] (assumes normal distribution)


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
# Warmup Iteration   1: 15.487 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.872 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.005 ms/op
Iteration   1: 4.592 ±(99.9%) 0.012 ms/op
Iteration   2: 4.527 ±(99.9%) 0.012 ms/op
Iteration   3: 4.395 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.504 ±(99.9%) 1.832 ms/op [Average]
  (min, avg, max) = (4.395, 4.504, 4.592), stdev = 0.100
  CI (99.9%): [2.673, 6.336] (assumes normal distribution)


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
# Warmup Iteration   1: 12.565 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.017 ms/op
Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  23.382 ms/op
                 createUser·p0.9999: 25.877 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 4.009 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.058 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  25.559 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  18.784 ms/op
                 createUser·p0.9999: 33.490 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240029
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 469 
    [ 2.500,  5.000) = 225715 
    [ 5.000,  7.500) = 12429 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     23.395 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     33.987 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 11.316 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
Iteration   1: 3.868 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  24.008 ms/op
                 existUser·p0.9999: 33.495 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   2: 3.850 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 33.290 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   3: 3.976 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  24.281 ms/op
                 existUser·p0.9999: 32.702 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246092
  mean =      3.897 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 406 
    [ 2.500,  5.000) = 235190 
    [ 5.000,  7.500) = 7788 
    [ 7.500, 10.000) = 2034 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 56 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     20.380 ms/op
     p(99.9900) =     33.227 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 12.335 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.013 ms/op
Iteration   1: 3.628 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  20.644 ms/op
                 getUser·p0.9999: 22.911 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 3.839 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  17.641 ms/op
                 getUser·p0.9999: 24.041 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.890 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.897 ms/op
                 getUser·p0.999:  25.788 ms/op
                 getUser·p0.9999: 31.588 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253649
  mean =      3.782 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 933 
    [ 2.500,  5.000) = 243224 
    [ 5.000,  7.500) = 7388 
    [ 7.500, 10.000) = 1517 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     30.418 ms/op
     p(99.9990) =     32.000 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 12.958 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.369 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.017 ms/op
Iteration   1: 4.540 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  22.348 ms/op
                 listUser·p0.9999: 24.083 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 4.788 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  17.574 ms/op
                 listUser·p0.9999: 21.153 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 4.533 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.201 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207890
  mean =      4.618 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 175122 
    [ 5.000,  7.500) = 28444 
    [ 7.500, 10.000) = 3280 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     24.765 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.988 ± 5.376  ops/ms
ClientPb.existUser                       thrpt       3   8.693 ± 2.927  ops/ms
ClientPb.getUser                         thrpt       3   8.519 ± 4.154  ops/ms
ClientPb.listUser                        thrpt       3   7.452 ± 6.802  ops/ms
ClientPb.createUser                       avgt       3   3.894 ± 1.651   ms/op
ClientPb.existUser                        avgt       3   3.555 ± 0.512   ms/op
ClientPb.getUser                          avgt       3   3.912 ± 1.323   ms/op
ClientPb.listUser                         avgt       3   4.504 ± 1.832   ms/op
ClientPb.createUser                     sample  240029   3.999 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.325           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.395           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.785           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  246092   3.897 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.809           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.380           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  253649   3.782 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.489           ms/op
ClientPb.listUser                       sample  207890   4.618 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.657           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
