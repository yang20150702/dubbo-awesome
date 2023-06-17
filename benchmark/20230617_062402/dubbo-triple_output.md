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
# Warmup Iteration   1: 1.098 ops/ms
# Warmup Iteration   2: 2.121 ops/ms
# Warmup Iteration   3: 4.888 ops/ms
Iteration   1: 5.283 ops/ms
Iteration   2: 5.720 ops/ms
Iteration   3: 5.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.579 ±(99.9%) 4.676 ops/ms [Average]
  (min, avg, max) = (5.283, 5.579, 5.734), stdev = 0.256
  CI (99.9%): [0.903, 10.255] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.719 ops/ms
# Warmup Iteration   2: 4.863 ops/ms
# Warmup Iteration   3: 5.861 ops/ms
Iteration   1: 6.032 ops/ms
Iteration   2: 6.450 ops/ms
Iteration   3: 6.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.233 ±(99.9%) 3.822 ops/ms [Average]
  (min, avg, max) = (6.032, 6.233, 6.450), stdev = 0.210
  CI (99.9%): [2.411, 10.056] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.171 ops/ms
# Warmup Iteration   3: 5.700 ops/ms
Iteration   1: 5.382 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.531 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (5.382, 5.531, 5.616), stdev = 0.130
  CI (99.9%): [3.168, 7.893] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.500 ops/ms
# Warmup Iteration   2: 4.215 ops/ms
# Warmup Iteration   3: 4.829 ops/ms
Iteration   1: 5.018 ops/ms
Iteration   2: 5.003 ops/ms
Iteration   3: 5.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.033 ±(99.9%) 0.720 ops/ms [Average]
  (min, avg, max) = (5.003, 5.033, 5.078), stdev = 0.039
  CI (99.9%): [4.313, 5.753] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.981 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.921 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.819 ±(99.9%) 0.010 ms/op
Iteration   1: 5.696 ±(99.9%) 0.012 ms/op
Iteration   2: 5.468 ±(99.9%) 0.011 ms/op
Iteration   3: 5.543 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.569 ±(99.9%) 2.126 ms/op [Average]
  (min, avg, max) = (5.468, 5.569, 5.696), stdev = 0.117
  CI (99.9%): [3.443, 7.695] (assumes normal distribution)


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
# Warmup Iteration   1: 16.170 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.062 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.534 ±(99.9%) 0.009 ms/op
Iteration   1: 5.516 ±(99.9%) 0.010 ms/op
Iteration   2: 5.164 ±(99.9%) 0.010 ms/op
Iteration   3: 5.367 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.349 ±(99.9%) 3.225 ms/op [Average]
  (min, avg, max) = (5.164, 5.349, 5.516), stdev = 0.177
  CI (99.9%): [2.124, 8.574] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.026 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.766 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.607 ±(99.9%) 0.015 ms/op
Iteration   1: 5.789 ±(99.9%) 0.012 ms/op
Iteration   2: 5.803 ±(99.9%) 0.008 ms/op
Iteration   3: 5.512 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.701 ±(99.9%) 2.996 ms/op [Average]
  (min, avg, max) = (5.512, 5.701, 5.803), stdev = 0.164
  CI (99.9%): [2.705, 8.698] (assumes normal distribution)


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
# Warmup Iteration   1: 18.732 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.701 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.718 ±(99.9%) 0.014 ms/op
Iteration   1: 6.597 ±(99.9%) 0.011 ms/op
Iteration   2: 6.357 ±(99.9%) 0.011 ms/op
Iteration   3: 6.425 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.460 ±(99.9%) 2.254 ms/op [Average]
  (min, avg, max) = (6.357, 6.460, 6.597), stdev = 0.124
  CI (99.9%): [4.206, 8.713] (assumes normal distribution)


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
# Warmup Iteration   1: 18.022 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 7.054 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.795 ±(99.9%) 0.026 ms/op
Iteration   1: 5.591 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   10.524 ms/op
                 createUser·p0.999:  22.670 ms/op
                 createUser·p0.9999: 28.288 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 5.653 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.216 ms/op
                 createUser·p0.95:   8.241 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  27.111 ms/op
                 createUser·p0.9999: 32.474 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 5.686 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 30.929 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170070
  mean =      5.643 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 63445 
    [ 5.000,  7.500) = 92158 
    [ 7.500, 10.000) = 11685 
    [10.000, 12.500) = 1993 
    [12.500, 15.000) = 413 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.258 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     33.665 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 16.368 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.022 ms/op
Iteration   1: 5.520 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   7.954 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  20.647 ms/op
                 existUser·p0.9999: 25.389 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 5.297 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   7.963 ms/op
                 existUser·p0.99:   11.235 ms/op
                 existUser·p0.999:  15.803 ms/op
                 existUser·p0.9999: 26.345 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 5.391 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  23.618 ms/op
                 existUser·p0.9999: 27.658 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177722
  mean =      5.401 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 84671 
    [ 5.000,  7.500) = 81359 
    [ 7.500, 10.000) = 9143 
    [10.000, 12.500) = 1731 
    [12.500, 15.000) = 503 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     19.706 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     28.421 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 17.254 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.670 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.062 ±(99.9%) 0.025 ms/op
Iteration   1: 5.674 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.176 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.392 ms/op
                 getUser·p0.999:  24.531 ms/op
                 getUser·p0.9999: 26.658 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   2: 5.384 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.716 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  23.902 ms/op
                 getUser·p0.9999: 29.696 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   3: 5.785 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.638 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.243 ms/op
                 getUser·p0.999:  27.394 ms/op
                 getUser·p0.9999: 40.989 ms/op
                 getUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170942
  mean =      5.609 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 65303 
    [ 5.000, 10.000) = 102752 
    [10.000, 15.000) = 2569 
    [15.000, 20.000) = 123 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.638 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     24.480 ms/op
     p(99.9900) =     38.928 ms/op
     p(99.9990) =     41.402 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 20.325 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 7.760 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.400 ±(99.9%) 0.024 ms/op
Iteration   1: 6.435 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  27.246 ms/op
                 listUser·p0.9999: 30.439 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   2: 6.557 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.809 ms/op
                 listUser·p0.999:  27.623 ms/op
                 listUser·p0.9999: 30.509 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   3: 6.712 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.476 ms/op
                 listUser·p0.999:  24.777 ms/op
                 listUser·p0.9999: 30.384 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146149
  mean =      6.566 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 13905 
    [ 5.000,  7.500) = 104533 
    [ 7.500, 10.000) = 22541 
    [10.000, 12.500) = 3715 
    [12.500, 15.000) = 844 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      6.218 ms/op
     p(90.0000) =      8.380 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     27.127 ms/op
     p(99.9900) =     30.389 ms/op
     p(99.9990) =     32.345 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.579 ± 4.676  ops/ms
ClientPb.existUser                       thrpt       3   6.233 ± 3.822  ops/ms
ClientPb.getUser                         thrpt       3   5.531 ± 2.363  ops/ms
ClientPb.listUser                        thrpt       3   5.033 ± 0.720  ops/ms
ClientPb.createUser                       avgt       3   5.569 ± 2.126   ms/op
ClientPb.existUser                        avgt       3   5.349 ± 3.225   ms/op
ClientPb.getUser                          avgt       3   5.701 ± 2.996   ms/op
ClientPb.listUser                         avgt       3   6.460 ± 2.254   ms/op
ClientPb.createUser                     sample  170070   5.643 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.249           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.413           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.031           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  177722   5.401 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.585           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.071           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.848           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.706           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.903           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  170942   5.609 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.119           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.912           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.928           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.681           ms/op
ClientPb.listUser                       sample  146149   6.566 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.380           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.127           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.768           ms/op
