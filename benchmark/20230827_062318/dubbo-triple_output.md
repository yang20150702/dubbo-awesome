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
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 3.425 ops/ms
# Warmup Iteration   3: 6.893 ops/ms
Iteration   1: 7.603 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.732 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (7.603, 7.732, 7.806), stdev = 0.112
  CI (99.9%): [5.696, 9.768] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 6.703 ops/ms
# Warmup Iteration   3: 7.776 ops/ms
Iteration   1: 8.457 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.495 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (8.457, 8.495, 8.520), stdev = 0.033
  CI (99.9%): [7.890, 9.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.043 ops/ms
# Warmup Iteration   3: 7.872 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.974 ±(99.9%) 2.980 ops/ms [Average]
  (min, avg, max) = (7.806, 7.974, 8.133), stdev = 0.163
  CI (99.9%): [4.994, 10.954] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.076 ops/ms
# Warmup Iteration   3: 6.400 ops/ms
Iteration   1: 6.583 ops/ms
Iteration   2: 6.818 ops/ms
Iteration   3: 6.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.719 ±(99.9%) 2.226 ops/ms [Average]
  (min, avg, max) = (6.583, 6.719, 6.818), stdev = 0.122
  CI (99.9%): [4.493, 8.945] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.554 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.007 ms/op
Iteration   1: 4.193 ±(99.9%) 0.008 ms/op
Iteration   2: 4.025 ±(99.9%) 0.008 ms/op
Iteration   3: 3.987 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.068 ±(99.9%) 2.002 ms/op [Average]
  (min, avg, max) = (3.987, 4.068, 4.193), stdev = 0.110
  CI (99.9%): [2.066, 6.070] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.007 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.010 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
Iteration   2: 4.055 ±(99.9%) 0.003 ms/op
Iteration   3: 3.878 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.938 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (3.878, 3.938, 4.055), stdev = 0.101
  CI (99.9%): [2.090, 5.787] (assumes normal distribution)


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
# Warmup Iteration   1: 12.427 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.005 ms/op
Iteration   1: 4.179 ±(99.9%) 0.003 ms/op
Iteration   2: 4.039 ±(99.9%) 0.005 ms/op
Iteration   3: 4.079 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.099 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (4.039, 4.099, 4.179), stdev = 0.072
  CI (99.9%): [2.784, 5.414] (assumes normal distribution)


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
# Warmup Iteration   1: 13.582 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.420 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.013 ms/op
Iteration   1: 4.987 ±(99.9%) 0.009 ms/op
Iteration   2: 4.823 ±(99.9%) 0.008 ms/op
Iteration   3: 4.813 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.874 ±(99.9%) 1.784 ms/op [Average]
  (min, avg, max) = (4.813, 4.874, 4.987), stdev = 0.098
  CI (99.9%): [3.090, 6.659] (assumes normal distribution)


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
# Warmup Iteration   1: 13.080 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.020 ms/op
Iteration   1: 4.120 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  23.834 ms/op
                 createUser·p0.9999: 33.333 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  14.418 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   3: 3.970 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   7.607 ms/op
                 createUser·p0.999:  29.698 ms/op
                 createUser·p0.9999: 37.483 ms/op
                 createUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238528
  mean =      4.022 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 226027 
    [ 5.000, 10.000) = 11598 
    [10.000, 15.000) = 611 
    [15.000, 20.000) = 26 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 104 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.862 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     35.549 ms/op
     p(99.9990) =     37.592 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 12.359 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
Iteration   1: 4.140 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.666 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  23.974 ms/op
                 existUser·p0.9999: 30.999 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  13.158 ms/op
                 existUser·p0.9999: 28.502 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 4.002 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   8.192 ms/op
                 existUser·p0.999:  13.665 ms/op
                 existUser·p0.9999: 30.540 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239150
  mean =      4.014 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 224154 
    [ 5.000,  7.500) = 11355 
    [ 7.500, 10.000) = 2554 
    [10.000, 12.500) = 497 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     14.601 ms/op
     p(99.9900) =     30.190 ms/op
     p(99.9990) =     31.444 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.166 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.796 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.015 ms/op
Iteration   1: 4.069 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.091 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 29.786 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  12.062 ms/op
                 getUser·p0.9999: 28.124 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 4.087 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.200 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  28.148 ms/op
                 getUser·p0.9999: 30.388 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235533
  mean =      4.073 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 218609 
    [ 5.000,  7.500) = 13148 
    [ 7.500, 10.000) = 2794 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     32.374 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 15.387 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.616 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.019 ms/op
Iteration   1: 4.868 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   10.156 ms/op
                 listUser·p0.999:  25.405 ms/op
                 listUser·p0.9999: 28.382 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.816 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  20.260 ms/op
                 listUser·p0.9999: 28.127 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 4.852 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   9.665 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.986 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198107
  mean =      4.845 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 159945 
    [ 5.000,  7.500) = 31189 
    [ 7.500, 10.000) = 5023 
    [10.000, 12.500) = 1271 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     21.915 ms/op
     p(99.9900) =     27.812 ms/op
     p(99.9990) =     29.795 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.732 ± 2.036  ops/ms
ClientPb.existUser                       thrpt       3   8.495 ± 0.606  ops/ms
ClientPb.getUser                         thrpt       3   7.974 ± 2.980  ops/ms
ClientPb.listUser                        thrpt       3   6.719 ± 2.226  ops/ms
ClientPb.createUser                       avgt       3   4.068 ± 2.002   ms/op
ClientPb.existUser                        avgt       3   3.938 ± 1.849   ms/op
ClientPb.getUser                          avgt       3   4.099 ± 1.315   ms/op
ClientPb.listUser                         avgt       3   4.874 ± 1.784   ms/op
ClientPb.createUser                     sample  238528   4.022 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.321           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.862           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.549           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.436           ms/op
ClientPb.existUser                      sample  239150   4.014 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.667           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.208           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.601           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.190           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  235533   4.073 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.313           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.167           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.179           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.292           ms/op
ClientPb.listUser                       sample  198107   4.845 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.961           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.915           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.812           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
