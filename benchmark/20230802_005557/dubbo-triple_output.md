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
# Warmup Iteration   1: 1.607 ops/ms
# Warmup Iteration   2: 3.562 ops/ms
# Warmup Iteration   3: 6.810 ops/ms
Iteration   1: 7.306 ops/ms
Iteration   2: 7.728 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.631 ±(99.9%) 5.283 ops/ms [Average]
  (min, avg, max) = (7.306, 7.631, 7.860), stdev = 0.290
  CI (99.9%): [2.349, 12.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 6.763 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.200 ±(99.9%) 1.759 ops/ms [Average]
  (min, avg, max) = (8.107, 8.200, 8.299), stdev = 0.096
  CI (99.9%): [6.441, 9.959] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.056 ops/ms
# Warmup Iteration   2: 5.872 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 8.375 ops/ms
Iteration   3: 7.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.963 ±(99.9%) 7.120 ops/ms [Average]
  (min, avg, max) = (7.598, 7.963, 8.375), stdev = 0.390
  CI (99.9%): [0.843, 15.083] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.987 ops/ms
# Warmup Iteration   2: 5.466 ops/ms
# Warmup Iteration   3: 6.461 ops/ms
Iteration   1: 6.505 ops/ms
Iteration   2: 6.629 ops/ms
Iteration   3: 6.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.685 ±(99.9%) 3.891 ops/ms [Average]
  (min, avg, max) = (6.505, 6.685, 6.920), stdev = 0.213
  CI (99.9%): [2.794, 10.576] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.837 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.942 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.005 ms/op
Iteration   1: 4.242 ±(99.9%) 0.007 ms/op
Iteration   2: 4.136 ±(99.9%) 0.010 ms/op
Iteration   3: 3.953 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.110 ±(99.9%) 2.673 ms/op [Average]
  (min, avg, max) = (3.953, 4.110, 4.242), stdev = 0.146
  CI (99.9%): [1.438, 6.783] (assumes normal distribution)


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
# Warmup Iteration   1: 12.603 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.008 ms/op
Iteration   1: 3.854 ±(99.9%) 0.006 ms/op
Iteration   2: 3.813 ±(99.9%) 0.008 ms/op
Iteration   3: 3.927 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.864 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.813, 3.864, 3.927), stdev = 0.058
  CI (99.9%): [2.814, 4.915] (assumes normal distribution)


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
# Warmup Iteration   1: 13.434 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.004 ms/op
Iteration   1: 4.034 ±(99.9%) 0.006 ms/op
Iteration   2: 4.275 ±(99.9%) 0.009 ms/op
Iteration   3: 4.276 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.195 ±(99.9%) 2.548 ms/op [Average]
  (min, avg, max) = (4.034, 4.195, 4.276), stdev = 0.140
  CI (99.9%): [1.647, 6.744] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.612 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.265 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.041 ±(99.9%) 0.008 ms/op
Iteration   1: 4.925 ±(99.9%) 0.004 ms/op
Iteration   2: 4.976 ±(99.9%) 0.009 ms/op
Iteration   3: 4.815 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.905 ±(99.9%) 1.503 ms/op [Average]
  (min, avg, max) = (4.815, 4.905, 4.976), stdev = 0.082
  CI (99.9%): [3.402, 6.408] (assumes normal distribution)


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
# Warmup Iteration   1: 12.511 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.291 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.021 ms/op
Iteration   1: 4.073 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 30.807 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.425 ms/op
                 createUser·p0.999:  12.638 ms/op
                 createUser·p0.9999: 28.586 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 4.183 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   8.237 ms/op
                 createUser·p0.999:  30.227 ms/op
                 createUser·p0.9999: 36.904 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234803
  mean =      4.089 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 288 
    [ 2.500,  5.000) = 217646 
    [ 5.000,  7.500) = 13444 
    [ 7.500, 10.000) = 2332 
    [10.000, 12.500) = 658 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     35.261 ms/op
     p(99.9990) =     37.749 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 13.612 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.165 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.015 ms/op
Iteration   1: 4.037 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  15.578 ms/op
                 existUser·p0.9999: 27.235 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.954 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  23.167 ms/op
                 existUser·p0.9999: 25.549 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.114 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  19.104 ms/op
                 existUser·p0.9999: 27.943 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241498
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 227783 
    [ 5.000,  7.500) = 9946 
    [ 7.500, 10.000) = 2419 
    [10.000, 12.500) = 619 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     19.186 ms/op
     p(99.9900) =     27.515 ms/op
     p(99.9990) =     28.167 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 15.478 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.016 ms/op
Iteration   1: 4.310 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  18.560 ms/op
                 getUser·p0.9999: 26.954 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 4.061 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.094 ms/op
                 getUser·p0.999:  11.815 ms/op
                 getUser·p0.9999: 27.136 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 4.321 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.091 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 28.606 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227147
  mean =      4.227 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 206594 
    [ 5.000,  7.500) = 15579 
    [ 7.500, 10.000) = 3757 
    [10.000, 12.500) = 705 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.974 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 15.263 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 6.287 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 4.802 ±(99.9%) 0.018 ms/op
Iteration   1: 4.746 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.564 ms/op
                 listUser·p0.999:  25.362 ms/op
                 listUser·p0.9999: 28.605 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 4.920 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 5.034 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   7.728 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  19.153 ms/op
                 listUser·p0.9999: 22.466 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195827
  mean =      4.897 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 152356 
    [ 5.000,  7.500) = 35309 
    [ 7.500, 10.000) = 5940 
    [10.000, 12.500) = 1420 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 171 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     30.061 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.631 ± 5.283  ops/ms
ClientPb.existUser                       thrpt       3   8.200 ± 1.759  ops/ms
ClientPb.getUser                         thrpt       3   7.963 ± 7.120  ops/ms
ClientPb.listUser                        thrpt       3   6.685 ± 3.891  ops/ms
ClientPb.createUser                       avgt       3   4.110 ± 2.673   ms/op
ClientPb.existUser                        avgt       3   3.864 ± 1.051   ms/op
ClientPb.getUser                          avgt       3   4.195 ± 2.548   ms/op
ClientPb.listUser                         avgt       3   4.905 ± 1.503   ms/op
ClientPb.createUser                     sample  234803   4.089 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.362           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.261           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  241498   3.975 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.579           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.077           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.186           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.515           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.836           ms/op
ClientPb.getUser                        sample  227147   4.227 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.720           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.733           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  195827   4.897 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.840           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.984           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.097           ms/op
