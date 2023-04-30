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
# Warmup Iteration   1: 0.978 ops/ms
# Warmup Iteration   2: 2.362 ops/ms
# Warmup Iteration   3: 4.848 ops/ms
Iteration   1: 5.473 ops/ms
Iteration   2: 5.635 ops/ms
Iteration   3: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.659 ±(99.9%) 3.633 ops/ms [Average]
  (min, avg, max) = (5.473, 5.659, 5.869), stdev = 0.199
  CI (99.9%): [2.025, 9.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 4.390 ops/ms
# Warmup Iteration   3: 5.759 ops/ms
Iteration   1: 5.964 ops/ms
Iteration   2: 5.938 ops/ms
Iteration   3: 5.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.916 ±(99.9%) 1.137 ops/ms [Average]
  (min, avg, max) = (5.846, 5.916, 5.964), stdev = 0.062
  CI (99.9%): [4.779, 7.052] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.656 ops/ms
# Warmup Iteration   2: 4.704 ops/ms
# Warmup Iteration   3: 5.896 ops/ms
Iteration   1: 5.749 ops/ms
Iteration   2: 5.731 ops/ms
Iteration   3: 6.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.854 ±(99.9%) 3.625 ops/ms [Average]
  (min, avg, max) = (5.731, 5.854, 6.084), stdev = 0.199
  CI (99.9%): [2.229, 9.479] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.229 ops/ms
# Warmup Iteration   3: 4.816 ops/ms
Iteration   1: 4.898 ops/ms
Iteration   2: 5.010 ops/ms
Iteration   3: 4.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.935 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (4.897, 4.935, 5.010), stdev = 0.065
  CI (99.9%): [3.751, 6.119] (assumes normal distribution)


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
# Warmup Iteration   1: 17.950 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.946 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.742 ±(99.9%) 0.009 ms/op
Iteration   1: 5.181 ±(99.9%) 0.017 ms/op
Iteration   2: 5.279 ±(99.9%) 0.018 ms/op
Iteration   3: 5.265 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.242 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (5.181, 5.242, 5.279), stdev = 0.053
  CI (99.9%): [4.277, 6.207] (assumes normal distribution)


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
# Warmup Iteration   1: 15.052 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.253 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.558 ±(99.9%) 0.010 ms/op
Iteration   1: 5.493 ±(99.9%) 0.007 ms/op
Iteration   2: 5.068 ±(99.9%) 0.018 ms/op
Iteration   3: 5.219 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.260 ±(99.9%) 3.933 ms/op [Average]
  (min, avg, max) = (5.068, 5.260, 5.493), stdev = 0.216
  CI (99.9%): [1.328, 9.193] (assumes normal distribution)


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
# Warmup Iteration   1: 15.782 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.655 ±(99.9%) 0.013 ms/op
Iteration   1: 5.589 ±(99.9%) 0.011 ms/op
Iteration   2: 5.449 ±(99.9%) 0.011 ms/op
Iteration   3: 5.496 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.511 ±(99.9%) 1.306 ms/op [Average]
  (min, avg, max) = (5.449, 5.511, 5.589), stdev = 0.072
  CI (99.9%): [4.205, 6.817] (assumes normal distribution)


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
# Warmup Iteration   1: 19.702 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.205 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.266 ±(99.9%) 0.016 ms/op
Iteration   1: 6.398 ±(99.9%) 0.015 ms/op
Iteration   2: 6.473 ±(99.9%) 0.016 ms/op
Iteration   3: 6.307 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.393 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (6.307, 6.393, 6.473), stdev = 0.083
  CI (99.9%): [4.875, 7.910] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.846 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.346 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.026 ms/op
Iteration   1: 5.317 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  23.619 ms/op
                 createUser·p0.9999: 28.493 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 5.501 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.679 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   9.428 ms/op
                 createUser·p0.999:  27.451 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 5.422 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.323 ms/op
                 createUser·p0.999:  14.091 ms/op
                 createUser·p0.9999: 29.953 ms/op
                 createUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177446
  mean =      5.412 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 80073 
    [ 5.000,  7.500) = 87535 
    [ 7.500, 10.000) = 7955 
    [10.000, 12.500) = 1457 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     15.424 ms/op
     p(99.9900) =     29.778 ms/op
     p(99.9990) =     30.952 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 14.147 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.722 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.187 ±(99.9%) 0.019 ms/op
Iteration   1: 5.154 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.390 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   9.414 ms/op
                 existUser·p0.999:  22.869 ms/op
                 existUser·p0.9999: 26.824 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 5.089 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.422 ms/op
                 existUser·p0.999:  25.727 ms/op
                 existUser·p0.9999: 32.169 ms/op
                 existUser·p1.00:   33.948 ms/op

Iteration   3: 5.510 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.274 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  15.826 ms/op
                 existUser·p0.9999: 36.123 ms/op
                 existUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182996
  mean =      5.244 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 100938 
    [ 5.000,  7.500) = 71963 
    [ 7.500, 10.000) = 7853 
    [10.000, 12.500) = 1423 
    [12.500, 15.000) = 470 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     36.842 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 18.302 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.490 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.601 ±(99.9%) 0.021 ms/op
Iteration   1: 5.578 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.552 ms/op
                 getUser·p0.99:   11.993 ms/op
                 getUser·p0.999:  24.808 ms/op
                 getUser·p0.9999: 29.044 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   2: 5.519 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  25.891 ms/op
                 getUser·p0.9999: 29.958 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   3: 5.589 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.527 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.208 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  16.588 ms/op
                 getUser·p0.9999: 31.157 ms/op
                 getUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172577
  mean =      5.562 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 69461 
    [ 5.000,  7.500) = 89425 
    [ 7.500, 10.000) = 10748 
    [10.000, 12.500) = 2029 
    [12.500, 15.000) = 427 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.086 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     24.590 ms/op
     p(99.9900) =     30.138 ms/op
     p(99.9990) =     32.878 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 18.998 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 7.910 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.433 ±(99.9%) 0.028 ms/op
Iteration   1: 6.653 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.039 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  26.494 ms/op
                 listUser·p0.9999: 30.231 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   2: 6.282 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.275 ms/op
                 listUser·p0.999:  30.150 ms/op
                 listUser·p0.9999: 37.678 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   3: 6.694 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.326 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   12.772 ms/op
                 listUser·p0.999:  24.385 ms/op
                 listUser·p0.9999: 31.020 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146877
  mean =      6.538 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7150 
    [ 5.000,  7.500) = 117069 
    [ 7.500, 10.000) = 17159 
    [10.000, 12.500) = 3832 
    [12.500, 15.000) = 1044 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.646 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      8.184 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     28.356 ms/op
     p(99.9900) =     34.070 ms/op
     p(99.9990) =     39.037 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.659 ± 3.633  ops/ms
ClientPb.existUser                       thrpt       3   5.916 ± 1.137  ops/ms
ClientPb.getUser                         thrpt       3   5.854 ± 3.625  ops/ms
ClientPb.listUser                        thrpt       3   4.935 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   5.242 ± 0.965   ms/op
ClientPb.existUser                        avgt       3   5.260 ± 3.933   ms/op
ClientPb.getUser                          avgt       3   5.511 ± 1.306   ms/op
ClientPb.listUser                         avgt       3   6.393 ± 1.517   ms/op
ClientPb.createUser                     sample  177446   5.412 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.635           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.424           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.778           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  182996   5.244 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.469           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.777           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.897           ms/op
ClientPb.getUser                        sample  172577   5.562 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.722           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.086           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.590           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.138           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.897           ms/op
ClientPb.listUser                       sample  146877   6.538 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.646           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.356           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.070           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
