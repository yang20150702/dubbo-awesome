# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.962 ops/ms
# Warmup Iteration   2: 2.065 ops/ms
# Warmup Iteration   3: 4.384 ops/ms
Iteration   1: 4.989 ops/ms
Iteration   2: 5.215 ops/ms
Iteration   3: 5.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.208 ±(99.9%) 3.951 ops/ms [Average]
  (min, avg, max) = (4.989, 5.208, 5.422), stdev = 0.217
  CI (99.9%): [1.257, 9.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.329 ops/ms
# Warmup Iteration   2: 3.807 ops/ms
# Warmup Iteration   3: 5.283 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.529 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.674 ±(99.9%) 2.899 ops/ms [Average]
  (min, avg, max) = (5.529, 5.674, 5.844), stdev = 0.159
  CI (99.9%): [2.774, 8.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.379 ops/ms
# Warmup Iteration   2: 4.049 ops/ms
# Warmup Iteration   3: 5.369 ops/ms
Iteration   1: 5.318 ops/ms
Iteration   2: 5.134 ops/ms
Iteration   3: 5.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.246 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (5.134, 5.246, 5.318), stdev = 0.099
  CI (99.9%): [3.446, 7.046] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.182 ops/ms
# Warmup Iteration   2: 3.399 ops/ms
# Warmup Iteration   3: 4.351 ops/ms
Iteration   1: 4.516 ops/ms
Iteration   2: 4.463 ops/ms
Iteration   3: 4.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.543 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (4.463, 4.543, 4.649), stdev = 0.096
  CI (99.9%): [2.796, 6.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 23.040 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 7.304 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.260 ±(99.9%) 0.016 ms/op
Iteration   1: 6.451 ±(99.9%) 0.010 ms/op
Iteration   2: 6.017 ±(99.9%) 0.012 ms/op
Iteration   3: 6.147 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.205 ±(99.9%) 4.067 ms/op [Average]
  (min, avg, max) = (6.017, 6.205, 6.451), stdev = 0.223
  CI (99.9%): [2.138, 10.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.443 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 7.227 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.982 ±(99.9%) 0.007 ms/op
Iteration   1: 5.986 ±(99.9%) 0.015 ms/op
Iteration   2: 5.840 ±(99.9%) 0.010 ms/op
Iteration   3: 5.833 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.887 ±(99.9%) 1.576 ms/op [Average]
  (min, avg, max) = (5.833, 5.887, 5.986), stdev = 0.086
  CI (99.9%): [4.310, 7.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.168 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.747 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.007 ±(99.9%) 0.018 ms/op
Iteration   1: 6.065 ±(99.9%) 0.013 ms/op
Iteration   2: 5.839 ±(99.9%) 0.013 ms/op
Iteration   3: 5.810 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.905 ±(99.9%) 2.541 ms/op [Average]
  (min, avg, max) = (5.810, 5.905, 6.065), stdev = 0.139
  CI (99.9%): [3.364, 8.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.669 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 9.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.603 ±(99.9%) 0.014 ms/op
Iteration   1: 7.187 ±(99.9%) 0.015 ms/op
Iteration   2: 7.037 ±(99.9%) 0.020 ms/op
Iteration   3: 7.213 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.145 ±(99.9%) 1.731 ms/op [Average]
  (min, avg, max) = (7.037, 7.145, 7.213), stdev = 0.095
  CI (99.9%): [5.414, 8.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 22.011 ±(99.9%) 0.409 ms/op
# Warmup Iteration   2: 8.368 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.526 ±(99.9%) 0.029 ms/op
Iteration   1: 6.213 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.720 ms/op
                 createUser·p0.50:   5.923 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   11.785 ms/op
                 createUser·p0.999:  27.249 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   2: 5.985 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.669 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   10.812 ms/op
                 createUser·p0.999:  28.393 ms/op
                 createUser·p0.9999: 33.914 ms/op
                 createUser·p1.00:   34.931 ms/op

Iteration   3: 6.282 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.740 ms/op
                 createUser·p0.50:   5.988 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   10.987 ms/op
                 createUser·p0.999:  31.113 ms/op
                 createUser·p0.9999: 35.373 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 155816
  mean =      6.157 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 16729 
    [ 5.000,  7.500) = 122746 
    [ 7.500, 10.000) = 13308 
    [10.000, 12.500) = 2159 
    [12.500, 15.000) = 396 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.535 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     28.738 ms/op
     p(99.9900) =     33.877 ms/op
     p(99.9990) =     36.913 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.860 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.677 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.977 ±(99.9%) 0.024 ms/op
Iteration   1: 5.894 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.712 ms/op
                 existUser·p0.50:   5.480 ms/op
                 existUser·p0.90:   7.512 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  15.593 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   32.473 ms/op

Iteration   2: 5.812 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.187 ms/op
                 existUser·p0.50:   5.439 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   11.469 ms/op
                 existUser·p0.999:  28.669 ms/op
                 existUser·p0.9999: 33.260 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   3: 5.974 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.710 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.036 ms/op
                 existUser·p0.99:   11.529 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 35.343 ms/op
                 existUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 162875
  mean =      5.892 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 28825 
    [ 5.000,  7.500) = 119805 
    [ 7.500, 10.000) = 10839 
    [10.000, 12.500) = 2441 
    [12.500, 15.000) = 575 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     36.004 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.386 ±(99.9%) 0.387 ms/op
# Warmup Iteration   2: 8.651 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.360 ±(99.9%) 0.023 ms/op
Iteration   1: 6.123 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.248 ms/op
                 getUser·p0.50:   5.857 ms/op
                 getUser·p0.90:   7.356 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.698 ms/op
                 getUser·p0.999:  26.968 ms/op
                 getUser·p0.9999: 38.099 ms/op
                 getUser·p1.00:   38.404 ms/op

Iteration   2: 6.201 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   3.445 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   12.966 ms/op
                 getUser·p0.999:  30.325 ms/op
                 getUser·p0.9999: 33.634 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   3: 6.209 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.834 ms/op
                 getUser·p0.50:   5.906 ms/op
                 getUser·p0.90:   7.684 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   11.305 ms/op
                 getUser·p0.999:  16.005 ms/op
                 getUser·p0.9999: 40.481 ms/op
                 getUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155328
  mean =      6.178 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14773 
    [ 5.000, 10.000) = 136450 
    [10.000, 15.000) = 3661 
    [15.000, 20.000) = 252 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 67 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.834 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     28.399 ms/op
     p(99.9900) =     39.221 ms/op
     p(99.9990) =     41.755 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.598 ±(99.9%) 0.434 ms/op
# Warmup Iteration   2: 9.462 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.540 ±(99.9%) 0.035 ms/op
Iteration   1: 7.243 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.056 ms/op
                 listUser·p0.50:   6.881 ms/op
                 listUser·p0.90:   8.929 ms/op
                 listUser·p0.95:   10.076 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  29.488 ms/op
                 listUser·p0.9999: 32.982 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 6.860 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.531 ms/op
                 listUser·p0.50:   6.472 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  31.949 ms/op
                 listUser·p0.9999: 35.412 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   3: 6.948 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  31.148 ms/op
                 listUser·p0.9999: 38.364 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136780
  mean =      7.013 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1715 
    [ 5.000,  7.500) = 101716 
    [ 7.500, 10.000) = 27648 
    [10.000, 12.500) = 4266 
    [12.500, 15.000) = 791 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 110 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      2.576 ms/op
     p(50.0000) =      6.636 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =      9.667 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     31.162 ms/op
     p(99.9900) =     37.049 ms/op
     p(99.9990) =     38.511 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.208 ± 3.951  ops/ms
ClientPb.existUser                       thrpt       3   5.674 ± 2.899  ops/ms
ClientPb.getUser                         thrpt       3   5.246 ± 1.800  ops/ms
ClientPb.listUser                        thrpt       3   4.543 ± 1.747  ops/ms
ClientPb.createUser                       avgt       3   6.205 ± 4.067   ms/op
ClientPb.existUser                        avgt       3   5.887 ± 1.576   ms/op
ClientPb.getUser                          avgt       3   5.905 ± 2.541   ms/op
ClientPb.listUser                         avgt       3   7.145 ± 1.731   ms/op
ClientPb.createUser                     sample  155816   6.157 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.503           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.738           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.011           ms/op
ClientPb.existUser                      sample  162875   5.892 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.187           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.405           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.305           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  155328   6.178 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.221           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.009           ms/op
ClientPb.listUser                       sample  136780   7.013 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.576           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.667           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.583           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.162           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.049           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.535           ms/op
