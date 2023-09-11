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
# Warmup Iteration   1: 1.073 ops/ms
# Warmup Iteration   2: 2.399 ops/ms
# Warmup Iteration   3: 5.060 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.529 ops/ms
Iteration   3: 5.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.609 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (5.524, 5.609, 5.775), stdev = 0.144
  CI (99.9%): [2.991, 8.227] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.696 ops/ms
# Warmup Iteration   2: 4.893 ops/ms
# Warmup Iteration   3: 5.656 ops/ms
Iteration   1: 5.833 ops/ms
Iteration   2: 6.062 ops/ms
Iteration   3: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.942 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (5.833, 5.942, 6.062), stdev = 0.115
  CI (99.9%): [3.840, 8.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.653 ops/ms
# Warmup Iteration   2: 4.434 ops/ms
# Warmup Iteration   3: 5.562 ops/ms
Iteration   1: 5.370 ops/ms
Iteration   2: 5.745 ops/ms
Iteration   3: 5.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.548 ±(99.9%) 3.431 ops/ms [Average]
  (min, avg, max) = (5.370, 5.548, 5.745), stdev = 0.188
  CI (99.9%): [2.117, 8.979] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.462 ops/ms
# Warmup Iteration   2: 3.817 ops/ms
# Warmup Iteration   3: 4.742 ops/ms
Iteration   1: 4.931 ops/ms
Iteration   2: 5.059 ops/ms
Iteration   3: 4.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.944 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (4.841, 4.944, 5.059), stdev = 0.109
  CI (99.9%): [2.950, 6.937] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.148 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.526 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.008 ms/op
Iteration   1: 5.712 ±(99.9%) 0.014 ms/op
Iteration   2: 5.775 ±(99.9%) 0.006 ms/op
Iteration   3: 5.611 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.699 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (5.611, 5.699, 5.775), stdev = 0.083
  CI (99.9%): [4.190, 7.209] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.129 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.478 ±(99.9%) 0.010 ms/op
Iteration   1: 5.434 ±(99.9%) 0.009 ms/op
Iteration   2: 5.362 ±(99.9%) 0.010 ms/op
Iteration   3: 5.408 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.401 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (5.362, 5.401, 5.434), stdev = 0.037
  CI (99.9%): [4.733, 6.070] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.105 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.910 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.908 ±(99.9%) 0.009 ms/op
Iteration   1: 5.748 ±(99.9%) 0.011 ms/op
Iteration   2: 5.656 ±(99.9%) 0.009 ms/op
Iteration   3: 5.735 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.713 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (5.656, 5.713, 5.748), stdev = 0.050
  CI (99.9%): [4.804, 6.621] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.999 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.525 ±(99.9%) 0.016 ms/op
Iteration   1: 6.567 ±(99.9%) 0.010 ms/op
Iteration   2: 6.376 ±(99.9%) 0.014 ms/op
Iteration   3: 6.570 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.504 ±(99.9%) 2.032 ms/op [Average]
  (min, avg, max) = (6.376, 6.504, 6.570), stdev = 0.111
  CI (99.9%): [4.472, 8.536] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.082 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.773 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.101 ±(99.9%) 0.026 ms/op
Iteration   1: 5.735 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  22.387 ms/op
                 createUser·p0.9999: 25.442 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 5.467 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.635 ms/op
                 createUser·p0.99:   10.353 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 27.306 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 5.626 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.093 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.774 ms/op
                 createUser·p0.99:   11.020 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 28.986 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171149
  mean =      5.607 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 53379 
    [ 5.000,  7.500) = 107352 
    [ 7.500, 10.000) = 8063 
    [10.000, 12.500) = 1658 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     27.055 ms/op
     p(99.9990) =     30.101 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 16.190 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.403 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.679 ±(99.9%) 0.021 ms/op
Iteration   1: 5.442 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.322 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  14.952 ms/op
                 existUser·p0.9999: 25.698 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 5.421 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.706 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  26.246 ms/op
                 existUser·p0.9999: 35.493 ms/op
                 existUser·p1.00:   36.241 ms/op

Iteration   3: 5.323 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.406 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  27.296 ms/op
                 existUser·p0.9999: 32.931 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177880
  mean =      5.395 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 84107 
    [ 5.000,  7.500) = 82880 
    [ 7.500, 10.000) = 8574 
    [10.000, 12.500) = 1593 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.659 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     33.896 ms/op
     p(99.9990) =     36.190 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.273 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.577 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.925 ±(99.9%) 0.022 ms/op
Iteration   1: 5.754 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.339 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   8.086 ms/op
                 getUser·p0.99:   10.830 ms/op
                 getUser·p0.999:  24.426 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 5.819 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   7.102 ms/op
                 getUser·p0.95:   8.864 ms/op
                 getUser·p0.99:   12.550 ms/op
                 getUser·p0.999:  17.935 ms/op
                 getUser·p0.9999: 29.722 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 5.615 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.056 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  26.623 ms/op
                 getUser·p0.9999: 33.988 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167425
  mean =      5.728 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 40351 
    [ 5.000,  7.500) = 115309 
    [ 7.500, 10.000) = 8499 
    [10.000, 12.500) = 2214 
    [12.500, 15.000) = 654 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     20.171 ms/op
     p(99.9900) =     33.309 ms/op
     p(99.9990) =     35.056 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 19.395 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.063 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.610 ±(99.9%) 0.025 ms/op
Iteration   1: 6.535 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  26.477 ms/op
                 listUser·p0.9999: 29.301 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 6.514 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.585 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.984 ms/op
                 listUser·p0.999:  29.721 ms/op
                 listUser·p0.9999: 37.362 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   3: 6.371 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   13.287 ms/op
                 listUser·p0.999:  22.886 ms/op
                 listUser·p0.9999: 32.799 ms/op
                 listUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148228
  mean =      6.472 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 4033 
    [ 5.000,  7.500) = 127448 
    [ 7.500, 10.000) = 10825 
    [10.000, 12.500) = 4035 
    [12.500, 15.000) = 1163 
    [15.000, 17.500) = 347 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     13.217 ms/op
     p(99.9000) =     27.019 ms/op
     p(99.9900) =     34.742 ms/op
     p(99.9990) =     37.521 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.609 ± 2.618  ops/ms
ClientPb.existUser                       thrpt       3   5.942 ± 2.102  ops/ms
ClientPb.getUser                         thrpt       3   5.548 ± 3.431  ops/ms
ClientPb.listUser                        thrpt       3   4.944 ± 1.993  ops/ms
ClientPb.createUser                       avgt       3   5.699 ± 1.510   ms/op
ClientPb.existUser                        avgt       3   5.401 ± 0.669   ms/op
ClientPb.getUser                          avgt       3   5.713 ± 0.909   ms/op
ClientPb.listUser                         avgt       3   6.504 ± 2.032   ms/op
ClientPb.createUser                     sample  171149   5.607 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.534           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.791           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.596           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.055           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474           ms/op
ClientPb.existUser                      sample  177880   5.395 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.659           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.889           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.453           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.268           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.896           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.241           ms/op
ClientPb.getUser                        sample  167425   5.728 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.914           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.307           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.469           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.171           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.309           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  148228   6.472 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.062           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.019           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.552           ms/op
