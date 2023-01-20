# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.562 ops/ms
# Warmup Iteration   2: 3.492 ops/ms
# Warmup Iteration   3: 7.072 ops/ms
Iteration   1: 7.378 ops/ms
Iteration   2: 8.186 ops/ms
Iteration   3: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.713 ±(99.9%) 7.687 ops/ms [Average]
  (min, avg, max) = (7.378, 7.713, 8.186), stdev = 0.421
  CI (99.9%): [0.026, 15.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 6.142 ops/ms
# Warmup Iteration   3: 7.538 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 7.835 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.958 ±(99.9%) 4.463 ops/ms [Average]
  (min, avg, max) = (7.800, 7.958, 8.240), stdev = 0.245
  CI (99.9%): [3.495, 12.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.543 ops/ms
# Warmup Iteration   2: 7.026 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.988 ±(99.9%) 0.796 ops/ms [Average]
  (min, avg, max) = (7.954, 7.988, 8.037), stdev = 0.044
  CI (99.9%): [7.192, 8.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 5.454 ops/ms
# Warmup Iteration   3: 6.793 ops/ms
Iteration   1: 6.743 ops/ms
Iteration   2: 6.809 ops/ms
Iteration   3: 6.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.647 ±(99.9%) 4.128 ops/ms [Average]
  (min, avg, max) = (6.389, 6.647, 6.809), stdev = 0.226
  CI (99.9%): [2.519, 10.776] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.150 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.008 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
Iteration   2: 3.999 ±(99.9%) 0.005 ms/op
Iteration   3: 4.145 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.027 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (3.937, 4.027, 4.145), stdev = 0.107
  CI (99.9%): [2.071, 5.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.125 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.854 ±(99.9%) 0.006 ms/op
Iteration   2: 4.020 ±(99.9%) 0.007 ms/op
Iteration   3: 3.822 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.899 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (3.822, 3.899, 4.020), stdev = 0.106
  CI (99.9%): [1.963, 5.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.300 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.005 ms/op
Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
Iteration   2: 3.854 ±(99.9%) 0.008 ms/op
Iteration   3: 4.085 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.995 ±(99.9%) 2.244 ms/op [Average]
  (min, avg, max) = (3.854, 3.995, 4.085), stdev = 0.123
  CI (99.9%): [1.750, 6.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.651 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.738 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.012 ms/op
Iteration   1: 4.620 ±(99.9%) 0.013 ms/op
Iteration   2: 4.649 ±(99.9%) 0.013 ms/op
Iteration   3: 4.779 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.683 ±(99.9%) 1.536 ms/op [Average]
  (min, avg, max) = (4.620, 4.683, 4.779), stdev = 0.084
  CI (99.9%): [3.147, 6.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.133 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.358 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.651 ±(99.9%) 0.021 ms/op
Iteration   1: 4.190 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.843 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  24.084 ms/op
                 createUser·p0.9999: 27.472 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.771 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 29.627 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 3.995 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  30.147 ms/op
                 createUser·p0.9999: 35.062 ms/op
                 createUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235987
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 219324 
    [ 5.000, 10.000) = 15701 
    [10.000, 15.000) = 656 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 157 
    [30.000, 35.000) = 81 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     25.428 ms/op
     p(99.9900) =     31.464 ms/op
     p(99.9990) =     43.558 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.699 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
Iteration   1: 3.939 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   7.700 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 24.638 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 3.729 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 23.915 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.752 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  25.578 ms/op
                 existUser·p0.9999: 33.060 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252459
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 243069 
    [ 5.000,  7.500) = 7003 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     29.254 ms/op
     p(99.9990) =     33.748 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.144 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.015 ms/op
Iteration   1: 4.024 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  24.874 ms/op
                 getUser·p0.9999: 32.475 ms/op
                 getUser·p1.00:   32.637 ms/op

Iteration   2: 3.899 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.769 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  11.446 ms/op
                 getUser·p0.9999: 30.585 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  25.684 ms/op
                 getUser·p0.9999: 30.629 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244281
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174 
    [ 2.500,  5.000) = 234683 
    [ 5.000,  7.500) = 7505 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     24.796 ms/op
     p(99.9900) =     31.991 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.270 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.483 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.957 ±(99.9%) 0.018 ms/op
Iteration   1: 4.763 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  24.248 ms/op
                 listUser·p0.9999: 29.491 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 4.955 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  19.509 ms/op
                 listUser·p0.9999: 21.907 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.682 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 20.617 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200050
  mean =      4.797 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 160555 
    [ 5.000,  7.500) = 32896 
    [ 7.500, 10.000) = 4993 
    [10.000, 12.500) = 944 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     20.020 ms/op
     p(99.9900) =     27.459 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.713 ± 7.687  ops/ms
ClientPb.existUser                       thrpt       3   7.958 ± 4.463  ops/ms
ClientPb.getUser                         thrpt       3   7.988 ± 0.796  ops/ms
ClientPb.listUser                        thrpt       3   6.647 ± 4.128  ops/ms
ClientPb.createUser                       avgt       3   4.027 ± 1.956   ms/op
ClientPb.existUser                        avgt       3   3.899 ± 1.936   ms/op
ClientPb.getUser                          avgt       3   3.995 ± 2.244   ms/op
ClientPb.listUser                         avgt       3   4.683 ± 1.536   ms/op
ClientPb.createUser                     sample  235987   4.064 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.922           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.428           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.464           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.713           ms/op
ClientPb.existUser                      sample  252459   3.804 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  244281   3.927 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.991           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.637           ms/op
ClientPb.listUser                       sample  200050   4.797 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.542           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.020           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.459           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
