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
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 6.640 ops/ms
# Warmup Iteration   3: 9.301 ops/ms
Iteration   1: 9.572 ops/ms
Iteration   2: 9.852 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.846 ±(99.9%) 4.944 ops/ms [Average]
  (min, avg, max) = (9.572, 9.846, 10.114), stdev = 0.271
  CI (99.9%): [4.902, 14.790] (assumes normal distribution)


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
# Warmup Iteration   1: 3.861 ops/ms
# Warmup Iteration   2: 9.636 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 9.971 ops/ms
Iteration   2: 10.256 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.233 ±(99.9%) 4.584 ops/ms [Average]
  (min, avg, max) = (9.971, 10.233, 10.472), stdev = 0.251
  CI (99.9%): [5.648, 14.817] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.887 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 10.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.072 ±(99.9%) 3.138 ops/ms [Average]
  (min, avg, max) = (9.887, 10.072, 10.226), stdev = 0.172
  CI (99.9%): [6.934, 13.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 7.642 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.324 ops/ms
Iteration   2: 8.531 ops/ms
Iteration   3: 8.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.546 ±(99.9%) 4.182 ops/ms [Average]
  (min, avg, max) = (8.324, 8.546, 8.782), stdev = 0.229
  CI (99.9%): [4.364, 12.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.958 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.005 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
Iteration   3: 3.284 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.179 ±(99.9%) 1.652 ms/op [Average]
  (min, avg, max) = (3.122, 3.179, 3.284), stdev = 0.091
  CI (99.9%): [1.527, 4.831] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 3.176 ±(99.9%) 0.005 ms/op
Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
Iteration   3: 3.004 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.147 ±(99.9%) 2.383 ms/op [Average]
  (min, avg, max) = (3.004, 3.147, 3.260), stdev = 0.131
  CI (99.9%): [0.764, 5.529] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.135 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.005 ms/op
Iteration   1: 3.235 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.004 ms/op
Iteration   3: 3.153 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.172 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.128, 3.172, 3.235), stdev = 0.056
  CI (99.9%): [2.154, 4.190] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.863 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.003 ms/op
Iteration   1: 3.862 ±(99.9%) 0.003 ms/op
Iteration   2: 3.623 ±(99.9%) 0.010 ms/op
Iteration   3: 3.730 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (3.623, 3.739, 3.862), stdev = 0.120
  CI (99.9%): [1.558, 5.919] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  10.453 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.021 ms/op
                 createUser·p0.9999: 20.768 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302964
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22418 
    [ 2.500,  5.000) = 274285 
    [ 5.000,  7.500) = 5424 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     13.108 ms/op
     p(99.9900) =     22.538 ms/op
     p(99.9990) =     24.176 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 23.642 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  12.638 ms/op
                 existUser·p0.9999: 22.595 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  13.206 ms/op
                 existUser·p0.9999: 19.123 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313840
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18580 
    [ 2.500,  5.000) = 290056 
    [ 5.000,  7.500) = 4360 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.473 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.502 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  15.177 ms/op
                 getUser·p0.9999: 22.972 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 28.645 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.864 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  12.352 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299132
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13003 
    [ 2.500,  5.000) = 278913 
    [ 5.000,  7.500) = 6295 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     29.689 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.660 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   8.018 ms/op
                 listUser·p0.999:  18.031 ms/op
                 listUser·p0.9999: 20.212 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.788 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   3: 3.704 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 14.933 ms/op
                 listUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252526
  mean =      3.802 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 240520 
    [ 5.000,  7.500) = 9441 
    [ 7.500, 10.000) = 1746 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.846 ± 4.944  ops/ms
ClientPb.existUser                       thrpt       3  10.233 ± 4.584  ops/ms
ClientPb.getUser                         thrpt       3  10.072 ± 3.138  ops/ms
ClientPb.listUser                        thrpt       3   8.546 ± 4.182  ops/ms
ClientPb.createUser                       avgt       3   3.179 ± 1.652   ms/op
ClientPb.existUser                        avgt       3   3.147 ± 2.383   ms/op
ClientPb.getUser                          avgt       3   3.172 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 2.180   ms/op
ClientPb.createUser                     sample  302964   3.170 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.108           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.538           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.281           ms/op
ClientPb.existUser                      sample  313840   3.058 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.962           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.576           ms/op
ClientPb.getUser                        sample  299132   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.844           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.080           ms/op
ClientPb.listUser                       sample  252526   3.802 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.447           ms/op
