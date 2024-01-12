# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.734 ops/ms
# Warmup Iteration   2: 11.979 ops/ms
# Warmup Iteration   3: 12.484 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.700 ops/ms
Iteration   3: 12.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.604 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (12.461, 12.604, 12.700), stdev = 0.127
  CI (99.9%): [10.296, 14.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.973 ops/ms
# Warmup Iteration   2: 13.321 ops/ms
# Warmup Iteration   3: 13.335 ops/ms
Iteration   1: 13.394 ops/ms
Iteration   2: 13.483 ops/ms
Iteration   3: 13.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.395 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (13.310, 13.395, 13.483), stdev = 0.087
  CI (99.9%): [11.814, 14.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.484 ops/ms
# Warmup Iteration   2: 12.242 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.872 ops/ms
Iteration   2: 12.771 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.761 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (12.641, 12.761, 12.872), stdev = 0.116
  CI (99.9%): [10.640, 14.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ops/ms
# Warmup Iteration   2: 10.648 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 10.815 ops/ms
Iteration   2: 10.822 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.772 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (10.680, 10.772, 10.822), stdev = 0.080
  CI (99.9%): [9.311, 12.234] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.461 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.455, 2.461, 2.470), stdev = 0.008
  CI (99.9%): [2.307, 2.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.458, 2.476, 2.495), stdev = 0.019
  CI (99.9%): [2.137, 2.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.451, 2.457, 2.466), stdev = 0.008
  CI (99.9%): [2.311, 2.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.513 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
Iteration   2: 2.941 ±(99.9%) 0.004 ms/op
Iteration   3: 2.950 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.950 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.941, 2.950, 2.958), stdev = 0.008
  CI (99.9%): [2.794, 3.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.274 ms/op
                 createUser·p0.9999: 14.243 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  10.374 ms/op
                 createUser·p0.9999: 14.012 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  8.764 ms/op
                 createUser·p0.9999: 10.916 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382067
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 185167 
    [ 2.500,  3.750) = 193128 
    [ 3.750,  5.000) = 3052 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.844 ms/op
     p(99.9900) =     13.657 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.322 ms/op
                 existUser·p0.999:  5.985 ms/op
                 existUser·p0.9999: 14.063 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.599 ms/op
                 existUser·p0.9999: 12.856 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.305 ms/op
                 existUser·p0.9999: 11.040 ms/op
                 existUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394432
  mean =      2.432 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 197054 
    [ 2.500,  3.750) = 194658 
    [ 3.750,  5.000) = 2017 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      5.714 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.468 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  9.078 ms/op
                 getUser·p0.9999: 14.408 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  9.185 ms/op
                 getUser·p0.9999: 12.696 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  9.363 ms/op
                 getUser·p0.9999: 11.620 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383603
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 191046 
    [ 2.500,  3.750) = 188901 
    [ 3.750,  5.000) = 2894 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      9.188 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     15.010 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 11.698 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   2: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.865 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323190
  mean =      2.967 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 103775 
    [ 2.500,  3.750) = 182582 
    [ 3.750,  5.000) = 29668 
    [ 5.000,  6.250) = 5549 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.698 ms/op
     p(99.9990) =     12.137 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.604 ± 2.309  ops/ms
ClientPb.existUser                       thrpt       3  13.395 ± 1.581  ops/ms
ClientPb.getUser                         thrpt       3  12.761 ± 2.122  ops/ms
ClientPb.listUser                        thrpt       3  10.772 ± 1.462  ops/ms
ClientPb.createUser                       avgt       3   2.461 ± 0.153   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.339   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.146   ms/op
ClientPb.listUser                         avgt       3   2.950 ± 0.155   ms/op
ClientPb.createUser                     sample  382067   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.725           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.844           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  394432   2.432 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.902           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.073           ms/op
ClientPb.getUser                        sample  383603   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.188           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.319           ms/op
ClientPb.listUser                       sample  323190   2.967 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.698           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
