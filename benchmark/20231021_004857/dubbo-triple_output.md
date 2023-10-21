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
# Warmup Iteration   1: 1.540 ops/ms
# Warmup Iteration   2: 3.304 ops/ms
# Warmup Iteration   3: 7.303 ops/ms
Iteration   1: 7.532 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.819 ±(99.9%) 4.643 ops/ms [Average]
  (min, avg, max) = (7.532, 7.819, 8.017), stdev = 0.255
  CI (99.9%): [3.176, 12.463] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.031 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 8.322 ops/ms
Iteration   2: 8.253 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.308 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (8.253, 8.308, 8.349), stdev = 0.050
  CI (99.9%): [7.400, 9.216] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.242 ops/ms
# Warmup Iteration   2: 7.105 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.117 ±(99.9%) 2.691 ops/ms [Average]
  (min, avg, max) = (7.954, 8.117, 8.241), stdev = 0.148
  CI (99.9%): [5.426, 10.808] (assumes normal distribution)


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
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 5.396 ops/ms
# Warmup Iteration   3: 6.358 ops/ms
Iteration   1: 6.561 ops/ms
Iteration   2: 6.594 ops/ms
Iteration   3: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.592 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (6.561, 6.592, 6.622), stdev = 0.031
  CI (99.9%): [6.035, 7.149] (assumes normal distribution)


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
# Warmup Iteration   1: 13.899 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.006 ms/op
Iteration   1: 3.986 ±(99.9%) 0.005 ms/op
Iteration   2: 3.978 ±(99.9%) 0.004 ms/op
Iteration   3: 4.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.022 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.978, 4.022, 4.103), stdev = 0.070
  CI (99.9%): [2.750, 5.294] (assumes normal distribution)


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
# Warmup Iteration   1: 12.170 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.008 ms/op
Iteration   1: 3.825 ±(99.9%) 0.005 ms/op
Iteration   2: 3.832 ±(99.9%) 0.006 ms/op
Iteration   3: 3.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.827 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (3.824, 3.827, 3.832), stdev = 0.004
  CI (99.9%): [3.746, 3.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.210 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.004 ms/op
Iteration   1: 4.075 ±(99.9%) 0.004 ms/op
Iteration   2: 4.011 ±(99.9%) 0.005 ms/op
Iteration   3: 4.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.033 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (4.011, 4.033, 4.075), stdev = 0.037
  CI (99.9%): [3.361, 4.704] (assumes normal distribution)


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
# Warmup Iteration   1: 13.406 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.932 ±(99.9%) 0.004 ms/op
Iteration   1: 4.814 ±(99.9%) 0.004 ms/op
Iteration   2: 4.904 ±(99.9%) 0.008 ms/op
Iteration   3: 4.828 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.849 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (4.814, 4.849, 4.904), stdev = 0.049
  CI (99.9%): [3.958, 5.739] (assumes normal distribution)


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
# Warmup Iteration   1: 13.373 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.018 ms/op
Iteration   1: 4.143 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  22.917 ms/op
                 createUser·p0.9999: 27.305 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 4.057 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.835 ms/op
                 createUser·p0.999:  14.225 ms/op
                 createUser·p0.9999: 26.939 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 4.028 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.181 ms/op
                 createUser·p0.999:  29.590 ms/op
                 createUser·p0.9999: 31.965 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235510
  mean =      4.076 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 220442 
    [ 5.000,  7.500) = 11829 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     31.112 ms/op
     p(99.9990) =     33.218 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 11.968 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.013 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.802 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   8.337 ms/op
                 existUser·p0.999:  11.712 ms/op
                 existUser·p0.9999: 22.803 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.844 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  9.253 ms/op
                 existUser·p0.9999: 24.500 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.945 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.505 ms/op
                 existUser·p0.999:  24.273 ms/op
                 existUser·p0.9999: 28.461 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245564
  mean =      3.910 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 539 
    [ 2.500,  5.000) = 235096 
    [ 5.000,  7.500) = 7286 
    [ 7.500, 10.000) = 1981 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     15.326 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.577 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 13.950 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
Iteration   1: 4.019 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  22.491 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.087 ms/op
                 getUser·p0.999:  10.921 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  26.816 ms/op
                 getUser·p0.9999: 29.035 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239956
  mean =      3.998 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 230767 
    [ 5.000,  7.500) = 7263 
    [ 7.500, 10.000) = 1201 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     22.480 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.002 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 14.713 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.540 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.879 ±(99.9%) 0.017 ms/op
Iteration   1: 4.828 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.256 ms/op
                 listUser·p0.999:  24.471 ms/op
                 listUser·p0.9999: 27.144 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 4.713 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.733 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 18.915 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201663
  mean =      4.757 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 165344 
    [ 5.000,  7.500) = 32925 
    [ 7.500, 10.000) = 2368 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     19.519 ms/op
     p(99.9900) =     26.700 ms/op
     p(99.9990) =     27.621 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.819 ± 4.643  ops/ms
ClientPb.existUser                       thrpt       3   8.308 ± 0.908  ops/ms
ClientPb.getUser                         thrpt       3   8.117 ± 2.691  ops/ms
ClientPb.listUser                        thrpt       3   6.592 ± 0.557  ops/ms
ClientPb.createUser                       avgt       3   4.022 ± 1.272   ms/op
ClientPb.existUser                        avgt       3   3.827 ± 0.080   ms/op
ClientPb.getUser                          avgt       3   4.033 ± 0.671   ms/op
ClientPb.listUser                         avgt       3   4.849 ± 0.891   ms/op
ClientPb.createUser                     sample  235510   4.076 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.946           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.112           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  245564   3.910 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.608           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.326           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  239956   3.998 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.344           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  201663   4.757 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.700           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
