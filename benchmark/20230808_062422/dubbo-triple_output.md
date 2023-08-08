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
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 3.439 ops/ms
# Warmup Iteration   3: 6.778 ops/ms
Iteration   1: 7.658 ops/ms
Iteration   2: 7.872 ops/ms
Iteration   3: 7.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.796 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (7.658, 7.796, 7.872), stdev = 0.119
  CI (99.9%): [5.617, 9.975] (assumes normal distribution)


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
# Warmup Iteration   1: 2.327 ops/ms
# Warmup Iteration   2: 6.857 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.619 ops/ms
Iteration   2: 8.461 ops/ms
Iteration   3: 8.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.594 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (8.461, 8.594, 8.700), stdev = 0.122
  CI (99.9%): [6.372, 10.815] (assumes normal distribution)


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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.366 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 8.278 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.113 ±(99.9%) 3.316 ops/ms [Average]
  (min, avg, max) = (7.918, 8.113, 8.278), stdev = 0.182
  CI (99.9%): [4.797, 11.429] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.893 ops/ms
# Warmup Iteration   3: 6.368 ops/ms
Iteration   1: 6.478 ops/ms
Iteration   2: 6.813 ops/ms
Iteration   3: 7.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.767 ±(99.9%) 4.901 ops/ms [Average]
  (min, avg, max) = (6.478, 6.767, 7.009), stdev = 0.269
  CI (99.9%): [1.865, 11.668] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.009 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.003 ms/op
Iteration   1: 4.045 ±(99.9%) 0.009 ms/op
Iteration   2: 3.976 ±(99.9%) 0.014 ms/op
Iteration   3: 4.067 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.029 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.976, 4.029, 4.067), stdev = 0.047
  CI (99.9%): [3.164, 4.895] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.211 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.004 ms/op
Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
Iteration   2: 3.839 ±(99.9%) 0.007 ms/op
Iteration   3: 3.769 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.836 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.769, 3.836, 3.901), stdev = 0.066
  CI (99.9%): [2.634, 5.038] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.774 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.486 ±(99.9%) 0.005 ms/op
Iteration   1: 4.272 ±(99.9%) 0.005 ms/op
Iteration   2: 4.205 ±(99.9%) 0.005 ms/op
Iteration   3: 4.059 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.179 ±(99.9%) 1.991 ms/op [Average]
  (min, avg, max) = (4.059, 4.179, 4.272), stdev = 0.109
  CI (99.9%): [2.187, 6.170] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.498 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.923 ±(99.9%) 0.009 ms/op
Iteration   1: 4.557 ±(99.9%) 0.010 ms/op
Iteration   2: 4.523 ±(99.9%) 0.014 ms/op
Iteration   3: 4.757 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.612 ±(99.9%) 2.302 ms/op [Average]
  (min, avg, max) = (4.523, 4.612, 4.757), stdev = 0.126
  CI (99.9%): [2.311, 6.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.157 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.023 ms/op
Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  26.214 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  19.706 ms/op
                 createUser·p0.9999: 31.304 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 4.081 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.038 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  15.368 ms/op
                 createUser·p0.9999: 33.003 ms/op
                 createUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235290
  mean =      4.078 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 240 
    [ 2.500,  5.000) = 218175 
    [ 5.000,  7.500) = 14541 
    [ 7.500, 10.000) = 1391 
    [10.000, 12.500) = 539 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     19.829 ms/op
     p(99.9900) =     31.768 ms/op
     p(99.9990) =     33.281 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 11.620 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   8.317 ms/op
                 existUser·p0.999:  18.778 ms/op
                 existUser·p0.9999: 21.760 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  16.822 ms/op
                 existUser·p0.9999: 24.145 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.966 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.659 ms/op
                 existUser·p0.999:  12.443 ms/op
                 existUser·p0.9999: 26.872 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240824
  mean =      3.984 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 352 
    [ 2.500,  5.000) = 222456 
    [ 5.000,  7.500) = 14694 
    [ 7.500, 10.000) = 2421 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.059 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     25.425 ms/op
     p(99.9990) =     27.451 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 13.528 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.016 ms/op
Iteration   1: 4.022 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.788 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  18.809 ms/op
                 getUser·p0.9999: 26.150 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 4.044 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  13.582 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   33.489 ms/op

Iteration   3: 4.188 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   8.557 ms/op
                 getUser·p0.999:  16.052 ms/op
                 getUser·p0.9999: 30.400 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235123
  mean =      4.083 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 216510 
    [ 5.000,  7.500) = 15228 
    [ 7.500, 10.000) = 1989 
    [10.000, 12.500) = 636 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     30.818 ms/op
     p(99.9990) =     33.466 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 12.957 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.622 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.019 ms/op
Iteration   1: 4.774 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   9.595 ms/op
                 listUser·p0.999:  23.859 ms/op
                 listUser·p0.9999: 25.930 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.877 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.950 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 22.523 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197236
  mean =      4.866 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 154249 
    [ 5.000,  7.500) = 35059 
    [ 7.500, 10.000) = 6055 
    [10.000, 12.500) = 1052 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     20.923 ms/op
     p(99.9900) =     25.118 ms/op
     p(99.9990) =     26.646 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.796 ± 2.179  ops/ms
ClientPb.existUser                       thrpt       3   8.594 ± 2.221  ops/ms
ClientPb.getUser                         thrpt       3   8.113 ± 3.316  ops/ms
ClientPb.listUser                        thrpt       3   6.767 ± 4.901  ops/ms
ClientPb.createUser                       avgt       3   4.029 ± 0.866   ms/op
ClientPb.existUser                        avgt       3   3.836 ± 1.202   ms/op
ClientPb.getUser                          avgt       3   4.179 ± 1.991   ms/op
ClientPb.listUser                         avgt       3   4.612 ± 2.302   ms/op
ClientPb.createUser                     sample  235290   4.078 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.007           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.471           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.829           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.768           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.325           ms/op
ClientPb.existUser                      sample  240824   3.984 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.059           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.843           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.656           ms/op
ClientPb.getUser                        sample  235123   4.083 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.602           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.818           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.489           ms/op
ClientPb.listUser                       sample  197236   4.866 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.929           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.923           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.118           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.837           ms/op
