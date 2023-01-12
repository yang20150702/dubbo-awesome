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
# Warmup Iteration   1: 2.676 ops/ms
# Warmup Iteration   2: 6.793 ops/ms
# Warmup Iteration   3: 9.261 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 9.852 ops/ms
Iteration   3: 9.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.842 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (9.790, 9.842, 9.883), stdev = 0.048
  CI (99.9%): [8.970, 10.713] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 8.772 ops/ms
# Warmup Iteration   3: 10.100 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.357 ±(99.9%) 9.759 ops/ms [Average]
  (min, avg, max) = (9.740, 10.357, 10.683), stdev = 0.535
  CI (99.9%): [0.598, 20.116] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 8.655 ops/ms
# Warmup Iteration   3: 9.718 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 9.649 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.059 ±(99.9%) 6.477 ops/ms [Average]
  (min, avg, max) = (9.649, 10.059, 10.283), stdev = 0.355
  CI (99.9%): [3.582, 16.536] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 8.619 ops/ms
Iteration   1: 8.645 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.645 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (8.564, 8.645, 8.726), stdev = 0.081
  CI (99.9%): [7.165, 10.125] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.289 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.003 ms/op
Iteration   1: 3.202 ±(99.9%) 0.009 ms/op
Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
Iteration   3: 3.022 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.151 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (3.022, 3.151, 3.229), stdev = 0.112
  CI (99.9%): [1.102, 5.200] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.641 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.005 ms/op
Iteration   1: 3.168 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.137 ±(99.9%) 1.804 ms/op [Average]
  (min, avg, max) = (3.026, 3.137, 3.217), stdev = 0.099
  CI (99.9%): [1.333, 4.941] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.412 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.294 ±(99.9%) 0.006 ms/op
Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
Iteration   3: 3.161 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.200 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.144, 3.200, 3.294), stdev = 0.082
  CI (99.9%): [1.706, 4.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.392 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.009 ms/op
Iteration   1: 3.698 ±(99.9%) 0.007 ms/op
Iteration   2: 3.659 ±(99.9%) 0.009 ms/op
Iteration   3: 3.765 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.659, 3.707, 3.765), stdev = 0.054
  CI (99.9%): [2.731, 4.683] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.593 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  14.995 ms/op
                 createUser·p0.9999: 19.881 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  14.532 ms/op
                 createUser·p0.9999: 22.480 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  14.564 ms/op
                 createUser·p0.9999: 20.960 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302276
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22361 
    [ 2.500,  5.000) = 273944 
    [ 5.000,  7.500) = 4978 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     14.605 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  13.703 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 19.506 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.943 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 21.743 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312296
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20069 
    [ 2.500,  5.000) = 288417 
    [ 5.000,  7.500) = 3225 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     10.560 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.688 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 7.729 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.011 ms/op
Iteration   1: 3.170 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.079 ms/op
                 getUser·p0.999:  16.188 ms/op
                 getUser·p0.9999: 20.444 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  9.314 ms/op
                 getUser·p0.9999: 23.129 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  11.716 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301090
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10022 
    [ 2.500,  5.000) = 284975 
    [ 5.000,  7.500) = 5023 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     22.410 ms/op
     p(99.9990) =     23.592 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.671 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.013 ms/op
Iteration   1: 3.766 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.846 ms/op
                 listUser·p0.9999: 18.268 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.870 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.654 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.099 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253014
  mean =      3.791 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 53 
    [ 2.500,  3.750) = 167447 
    [ 3.750,  5.000) = 76657 
    [ 5.000,  6.250) = 4550 
    [ 6.250,  7.500) = 2559 
    [ 7.500,  8.750) = 832 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 160 
    [13.750, 15.000) = 113 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 61 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.102 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.842 ± 0.872  ops/ms
ClientPb.existUser                       thrpt       3  10.357 ± 9.759  ops/ms
ClientPb.getUser                         thrpt       3  10.059 ± 6.477  ops/ms
ClientPb.listUser                        thrpt       3   8.645 ± 1.480  ops/ms
ClientPb.createUser                       avgt       3   3.151 ± 2.049   ms/op
ClientPb.existUser                        avgt       3   3.137 ± 1.804   ms/op
ClientPb.getUser                          avgt       3   3.200 ± 1.494   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 0.976   ms/op
ClientPb.createUser                     sample  302276   3.175 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.690           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.605           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.757           ms/op
ClientPb.existUser                      sample  312296   3.073 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.987           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.560           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.036           ms/op
ClientPb.getUser                        sample  301090   3.189 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.156           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.410           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  253014   3.791 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.333           ms/op
