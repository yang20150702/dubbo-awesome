# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.430 ops/ms
# Warmup Iteration   2: 3.287 ops/ms
# Warmup Iteration   3: 6.491 ops/ms
Iteration   1: 7.649 ops/ms
Iteration   2: 7.736 ops/ms
Iteration   3: 7.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.743 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (7.649, 7.743, 7.844), stdev = 0.098
  CI (99.9%): [5.960, 9.526] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.309 ops/ms
# Warmup Iteration   2: 6.719 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 8.443 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.367 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (8.276, 8.367, 8.443), stdev = 0.085
  CI (99.9%): [6.824, 9.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 6.919 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 8.140 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.034 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (7.956, 8.034, 8.140), stdev = 0.095
  CI (99.9%): [6.301, 9.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 6.060 ops/ms
# Warmup Iteration   3: 6.591 ops/ms
Iteration   1: 6.496 ops/ms
Iteration   2: 6.645 ops/ms
Iteration   3: 6.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.607 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (6.496, 6.607, 6.679), stdev = 0.098
  CI (99.9%): [4.826, 8.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.919 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.995 ±(99.9%) 0.004 ms/op
Iteration   2: 3.970 ±(99.9%) 0.007 ms/op
Iteration   3: 3.922 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.962 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.922, 3.962, 3.995), stdev = 0.037
  CI (99.9%): [3.280, 4.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.896 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.005 ms/op
Iteration   1: 3.696 ±(99.9%) 0.006 ms/op
Iteration   2: 3.910 ±(99.9%) 0.003 ms/op
Iteration   3: 3.746 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.784 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (3.696, 3.784, 3.910), stdev = 0.112
  CI (99.9%): [1.746, 5.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.356 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.003 ms/op
Iteration   1: 4.207 ±(99.9%) 0.005 ms/op
Iteration   2: 4.061 ±(99.9%) 0.005 ms/op
Iteration   3: 4.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.101 ±(99.9%) 1.693 ms/op [Average]
  (min, avg, max) = (4.034, 4.101, 4.207), stdev = 0.093
  CI (99.9%): [2.407, 5.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.935 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.006 ms/op
Iteration   1: 4.813 ±(99.9%) 0.007 ms/op
Iteration   2: 4.748 ±(99.9%) 0.007 ms/op
Iteration   3: 4.727 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.763 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (4.727, 4.763, 4.813), stdev = 0.044
  CI (99.9%): [3.953, 5.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.996 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.017 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 26.449 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  14.565 ms/op
                 createUser·p0.9999: 26.931 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.972 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  28.161 ms/op
                 createUser·p0.9999: 30.999 ms/op
                 createUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240423
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 423 
    [ 2.500,  5.000) = 230327 
    [ 5.000,  7.500) = 8043 
    [ 7.500, 10.000) = 976 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     30.044 ms/op
     p(99.9990) =     32.086 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.303 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  24.773 ms/op
                 existUser·p0.9999: 27.084 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.769 ms/op
                 existUser·p0.999:  13.705 ms/op
                 existUser·p0.9999: 30.004 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245851
  mean =      3.903 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 236522 
    [ 5.000,  7.500) = 7457 
    [ 7.500, 10.000) = 1024 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.811 ms/op
     p(99.9000) =     15.525 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     31.511 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.136 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.012 ms/op
Iteration   1: 4.114 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  13.802 ms/op
                 getUser·p0.9999: 24.288 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   2: 4.150 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  24.811 ms/op
                 getUser·p0.9999: 27.373 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 4.086 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.003 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  16.405 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233360
  mean =      4.116 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 221002 
    [ 5.000,  7.500) = 9713 
    [ 7.500, 10.000) = 1685 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.687 ms/op
     p(99.9000) =     20.966 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     29.404 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.926 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.605 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.960 ±(99.9%) 0.016 ms/op
Iteration   1: 4.867 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 25.882 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.858 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 24.636 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 4.785 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 18.218 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198222
  mean =      4.837 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 150902 
    [ 5.000,  7.500) = 42559 
    [ 7.500, 10.000) = 3564 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.036 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     25.407 ms/op
     p(99.9990) =     26.327 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.743 ± 1.783  ops/ms
ClientPb.existUser                       thrpt       3   8.367 ± 1.543  ops/ms
ClientPb.getUser                         thrpt       3   8.034 ± 1.733  ops/ms
ClientPb.listUser                        thrpt       3   6.607 ± 1.780  ops/ms
ClientPb.createUser                       avgt       3   3.962 ± 0.682   ms/op
ClientPb.existUser                        avgt       3   3.784 ± 2.038   ms/op
ClientPb.getUser                          avgt       3   4.101 ± 1.693   ms/op
ClientPb.listUser                         avgt       3   4.763 ± 0.809   ms/op
ClientPb.createUser                     sample  240423   3.991 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.384           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.044           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.637           ms/op
ClientPb.existUser                      sample  245851   3.903 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.811           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.525           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.443           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  233360   4.116 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.687           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.966           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.918           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  198222   4.837 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.036           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.407           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
