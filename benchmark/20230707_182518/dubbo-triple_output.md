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
# Warmup Iteration   1: 2.616 ops/ms
# Warmup Iteration   2: 6.762 ops/ms
# Warmup Iteration   3: 9.228 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 9.573 ops/ms
Iteration   3: 10.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.910 ±(99.9%) 6.789 ops/ms [Average]
  (min, avg, max) = (9.573, 9.910, 10.310), stdev = 0.372
  CI (99.9%): [3.121, 16.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 10.102 ops/ms
Iteration   1: 9.933 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.304 ±(99.9%) 5.857 ops/ms [Average]
  (min, avg, max) = (9.933, 10.304, 10.490), stdev = 0.321
  CI (99.9%): [4.447, 16.161] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 8.078 ops/ms
# Warmup Iteration   3: 9.791 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.027 ±(99.9%) 2.507 ops/ms [Average]
  (min, avg, max) = (9.871, 10.027, 10.129), stdev = 0.137
  CI (99.9%): [7.520, 12.535] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ops/ms
# Warmup Iteration   2: 7.923 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.700 ops/ms
Iteration   3: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.494 ±(99.9%) 3.247 ops/ms [Average]
  (min, avg, max) = (8.382, 8.494, 8.700), stdev = 0.178
  CI (99.9%): [5.247, 11.742] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.886 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.009 ms/op
Iteration   2: 3.276 ±(99.9%) 0.004 ms/op
Iteration   3: 3.203 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.201 ±(99.9%) 1.381 ms/op [Average]
  (min, avg, max) = (3.124, 3.201, 3.276), stdev = 0.076
  CI (99.9%): [1.820, 4.582] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.051 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
Iteration   3: 3.092 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (3.051, 3.087, 3.118), stdev = 0.034
  CI (99.9%): [2.474, 3.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.448 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
Iteration   3: 3.152 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.191 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.152, 3.191, 3.244), stdev = 0.047
  CI (99.9%): [2.327, 4.054] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.007 ms/op
Iteration   1: 3.782 ±(99.9%) 0.008 ms/op
Iteration   2: 3.716 ±(99.9%) 0.006 ms/op
Iteration   3: 3.704 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.734 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.704, 3.734, 3.782), stdev = 0.042
  CI (99.9%): [2.971, 4.497] (assumes normal distribution)


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
# Warmup Iteration   1: 8.081 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  9.409 ms/op
                 createUser·p0.9999: 20.606 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  15.335 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293302
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18141 
    [ 2.500,  5.000) = 269036 
    [ 5.000,  7.500) = 5243 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     25.352 ms/op
     p(99.9990) =     25.856 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.277 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.482 ms/op
                 existUser·p0.9999: 25.328 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  17.283 ms/op
                 existUser·p0.9999: 23.224 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306964
  mean =      3.126 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15720 
    [ 2.500,  5.000) = 285718 
    [ 5.000,  7.500) = 4768 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     13.406 ms/op
     p(99.9900) =     23.996 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 8.063 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
Iteration   1: 3.305 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 29.262 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 22.744 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.315 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  13.094 ms/op
                 getUser·p0.9999: 35.062 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292965
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18183 
    [ 2.500,  5.000) = 267143 
    [ 5.000,  7.500) = 6801 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     33.601 ms/op
     p(99.9990) =     35.399 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 9.708 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.011 ms/op
Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.592 ms/op
                 listUser·p0.999:  17.196 ms/op
                 listUser·p0.9999: 20.430 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 3.652 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   5.352 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 15.028 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.091 ms/op
                 listUser·p0.9999: 14.942 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257442
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 250977 
    [ 5.000,  7.500) = 4843 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     21.128 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.910 ± 6.789  ops/ms
ClientPb.existUser                       thrpt       3  10.304 ± 5.857  ops/ms
ClientPb.getUser                         thrpt       3  10.027 ± 2.507  ops/ms
ClientPb.listUser                        thrpt       3   8.494 ± 3.247  ops/ms
ClientPb.createUser                       avgt       3   3.201 ± 1.381   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 0.613   ms/op
ClientPb.getUser                          avgt       3   3.191 ± 0.863   ms/op
ClientPb.listUser                         avgt       3   3.734 ± 0.763   ms/op
ClientPb.createUser                     sample  293302   3.271 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.887           ms/op
ClientPb.existUser                      sample  306964   3.126 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.406           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.411           ms/op
ClientPb.getUser                        sample  292965   3.276 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  257442   3.726 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.337           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.603           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.759           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.413           ms/op
