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
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 5.764 ops/ms
# Warmup Iteration   3: 9.260 ops/ms
Iteration   1: 9.368 ops/ms
Iteration   2: 9.799 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.661 ±(99.9%) 4.631 ops/ms [Average]
  (min, avg, max) = (9.368, 9.661, 9.816), stdev = 0.254
  CI (99.9%): [5.030, 14.292] (assumes normal distribution)


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
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 9.520 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 9.899 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.211 ±(99.9%) 5.306 ops/ms [Average]
  (min, avg, max) = (9.899, 10.211, 10.475), stdev = 0.291
  CI (99.9%): [4.905, 15.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 9.680 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.021 ±(99.9%) 5.153 ops/ms [Average]
  (min, avg, max) = (9.755, 10.021, 10.317), stdev = 0.282
  CI (99.9%): [4.868, 15.174] (assumes normal distribution)


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
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.384 ops/ms
Iteration   1: 8.537 ops/ms
Iteration   2: 8.653 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (8.537, 8.599, 8.653), stdev = 0.058
  CI (99.9%): [7.533, 9.665] (assumes normal distribution)


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
# Warmup Iteration   1: 8.692 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.004 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
Iteration   3: 3.342 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.128, 3.222, 3.342), stdev = 0.110
  CI (99.9%): [1.223, 5.220] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.974 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.271 ±(99.9%) 0.007 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 2.511 ms/op [Average]
  (min, avg, max) = (3.024, 3.112, 3.271), stdev = 0.138
  CI (99.9%): [0.601, 5.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.426 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.003 ms/op
Iteration   1: 3.309 ±(99.9%) 0.003 ms/op
Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
Iteration   3: 3.159 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.159, 3.224, 3.309), stdev = 0.077
  CI (99.9%): [1.821, 4.627] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.508 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.007 ms/op
Iteration   1: 3.699 ±(99.9%) 0.011 ms/op
Iteration   2: 3.672 ±(99.9%) 0.012 ms/op
Iteration   3: 3.774 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.715 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.672, 3.715, 3.774), stdev = 0.052
  CI (99.9%): [2.757, 4.672] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.010 ms/op
Iteration   1: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 21.718 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.375 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.272 ms/op
                 createUser·p0.999:  18.801 ms/op
                 createUser·p0.9999: 22.955 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  13.812 ms/op
                 createUser·p0.9999: 21.357 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297930
  mean =      3.220 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14753 
    [ 2.500,  5.000) = 278617 
    [ 5.000,  7.500) = 3927 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.700 ms/op
     p(99.9900) =     22.649 ms/op
     p(99.9990) =     23.528 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 7.703 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.552 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 20.214 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.717 ms/op
                 existUser·p0.9999: 22.558 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.181 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   6.457 ms/op
                 existUser·p0.999:  13.083 ms/op
                 existUser·p0.9999: 23.393 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303026
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26131 
    [ 2.500,  5.000) = 270621 
    [ 5.000,  7.500) = 5346 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     22.547 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.778 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
Iteration   1: 3.210 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  18.330 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.993 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  8.540 ms/op
                 getUser·p0.9999: 21.752 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  14.425 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297931
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15861 
    [ 2.500,  5.000) = 274050 
    [ 5.000,  7.500) = 7175 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     15.555 ms/op
     p(99.9900) =     25.664 ms/op
     p(99.9990) =     27.493 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.421 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.012 ms/op
Iteration   1: 3.788 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 17.993 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.784 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   3: 3.877 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.617 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  12.592 ms/op
                 listUser·p0.9999: 15.786 ms/op
                 listUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251524
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 56 
    [ 2.500,  3.750) = 129093 
    [ 3.750,  5.000) = 115063 
    [ 5.000,  6.250) = 2820 
    [ 6.250,  7.500) = 2813 
    [ 7.500,  8.750) = 723 
    [ 8.750, 10.000) = 278 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 186 
    [12.500, 13.750) = 161 
    [13.750, 15.000) = 124 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     17.428 ms/op
     p(99.9990) =     18.788 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.661 ± 4.631  ops/ms
ClientPb.existUser                       thrpt       3  10.211 ± 5.306  ops/ms
ClientPb.getUser                         thrpt       3  10.021 ± 5.153  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 1.066  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 1.998   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 2.511   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 1.403   ms/op
ClientPb.listUser                         avgt       3   3.715 ± 0.958   ms/op
ClientPb.createUser                     sample  297930   3.220 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.649           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.593           ms/op
ClientPb.existUser                      sample  303026   3.165 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.042           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.547           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  297931   3.219 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.662           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.555           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.664           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  251524   3.816 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.169           ms/op
