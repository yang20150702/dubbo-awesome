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
# Warmup Iteration   1: 1.799 ops/ms
# Warmup Iteration   2: 3.896 ops/ms
# Warmup Iteration   3: 7.375 ops/ms
Iteration   1: 7.673 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.862 ±(99.9%) 4.609 ops/ms [Average]
  (min, avg, max) = (7.673, 7.862, 8.149), stdev = 0.253
  CI (99.9%): [3.253, 12.472] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.407 ops/ms
# Warmup Iteration   2: 7.282 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.436 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.372 ±(99.9%) 1.341 ops/ms [Average]
  (min, avg, max) = (8.292, 8.372, 8.436), stdev = 0.074
  CI (99.9%): [7.031, 9.713] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.460 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 7.877 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.203 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (8.148, 8.203, 8.243), stdev = 0.049
  CI (99.9%): [7.306, 9.099] (assumes normal distribution)


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
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 5.875 ops/ms
# Warmup Iteration   3: 6.523 ops/ms
Iteration   1: 6.788 ops/ms
Iteration   2: 6.810 ops/ms
Iteration   3: 6.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.777 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (6.733, 6.777, 6.810), stdev = 0.040
  CI (99.9%): [6.055, 7.499] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.453 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.004 ms/op
Iteration   1: 4.025 ±(99.9%) 0.005 ms/op
Iteration   2: 3.995 ±(99.9%) 0.008 ms/op
Iteration   3: 3.887 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.969 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.887, 3.969, 4.025), stdev = 0.072
  CI (99.9%): [2.646, 5.291] (assumes normal distribution)


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
# Warmup Iteration   1: 12.286 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.003 ms/op
Iteration   1: 3.805 ±(99.9%) 0.005 ms/op
Iteration   2: 3.821 ±(99.9%) 0.003 ms/op
Iteration   3: 3.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.848 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.805, 3.848, 3.917), stdev = 0.061
  CI (99.9%): [2.740, 4.955] (assumes normal distribution)


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
# Warmup Iteration   1: 12.569 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.003 ms/op
Iteration   1: 4.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.981 ±(99.9%) 0.005 ms/op
Iteration   3: 3.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.985 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.930, 3.985, 4.044), stdev = 0.057
  CI (99.9%): [2.950, 5.020] (assumes normal distribution)


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
# Warmup Iteration   1: 13.642 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.387 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.006 ms/op
Iteration   1: 4.732 ±(99.9%) 0.007 ms/op
Iteration   2: 4.787 ±(99.9%) 0.006 ms/op
Iteration   3: 4.660 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.726 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (4.660, 4.726, 4.787), stdev = 0.064
  CI (99.9%): [3.559, 5.893] (assumes normal distribution)


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
# Warmup Iteration   1: 12.791 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.017 ms/op
Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 23.667 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  23.588 ms/op
                 createUser·p0.9999: 27.976 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  25.991 ms/op
                 createUser·p0.9999: 30.009 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240754
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 591 
    [ 2.500,  5.000) = 228256 
    [ 5.000,  7.500) = 10260 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     21.602 ms/op
     p(99.9900) =     28.796 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 12.505 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.013 ms/op
Iteration   1: 3.792 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.801 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.126 ms/op
                 existUser·p0.999:  24.478 ms/op
                 existUser·p0.9999: 28.218 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251219
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 464 
    [ 2.500,  5.000) = 241836 
    [ 5.000,  7.500) = 6888 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.224 ms/op
     p(99.9000) =     16.967 ms/op
     p(99.9900) =     27.189 ms/op
     p(99.9990) =     28.556 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 11.885 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.013 ms/op
Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  23.028 ms/op
                 getUser·p0.9999: 26.161 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.243 ms/op
                 getUser·p0.999:  18.042 ms/op
                 getUser·p0.9999: 28.510 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  26.272 ms/op
                 getUser·p0.9999: 28.997 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239134
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 229715 
    [ 5.000,  7.500) = 6923 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 615 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     23.031 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.577 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 14.308 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.592 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.967 ±(99.9%) 0.017 ms/op
Iteration   1: 4.848 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 26.300 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.810 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  19.027 ms/op
                 listUser·p0.9999: 33.227 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 4.713 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  18.167 ms/op
                 listUser·p0.9999: 20.232 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200087
  mean =      4.790 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 157045 
    [ 5.000,  7.500) = 39451 
    [ 7.500, 10.000) = 2546 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 171 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.472 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     33.325 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.862 ± 4.609  ops/ms
ClientPb.existUser                       thrpt       3   8.372 ± 1.341  ops/ms
ClientPb.getUser                         thrpt       3   8.203 ± 0.896  ops/ms
ClientPb.listUser                        thrpt       3   6.777 ± 0.722  ops/ms
ClientPb.createUser                       avgt       3   3.969 ± 1.323   ms/op
ClientPb.existUser                        avgt       3   3.848 ± 1.107   ms/op
ClientPb.getUser                          avgt       3   3.985 ± 1.035   ms/op
ClientPb.listUser                         avgt       3   4.726 ± 1.167   ms/op
ClientPb.createUser                     sample  240754   3.988 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  251219   3.820 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.967           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.869           ms/op
ClientPb.getUser                        sample  239134   4.012 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  200087   4.790 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.472           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.464           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.018           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.144           ms/op
