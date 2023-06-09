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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 5.879 ops/ms
# Warmup Iteration   3: 9.296 ops/ms
Iteration   1: 9.918 ops/ms
Iteration   2: 9.741 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.927 ±(99.9%) 3.466 ops/ms [Average]
  (min, avg, max) = (9.741, 9.927, 10.121), stdev = 0.190
  CI (99.9%): [6.461, 13.392] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ops/ms
# Warmup Iteration   2: 9.522 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.322 ±(99.9%) 6.299 ops/ms [Average]
  (min, avg, max) = (9.928, 10.322, 10.574), stdev = 0.345
  CI (99.9%): [4.023, 16.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 9.205 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.055 ops/ms
Iteration   3: 9.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.031 ±(99.9%) 6.574 ops/ms [Average]
  (min, avg, max) = (9.659, 10.031, 10.379), stdev = 0.360
  CI (99.9%): [3.457, 16.605] (assumes normal distribution)


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
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.637 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.559 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (8.472, 8.559, 8.637), stdev = 0.083
  CI (99.9%): [7.040, 10.077] (assumes normal distribution)


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
Iteration   2: 3.399 ±(99.9%) 0.007 ms/op
Iteration   3: 3.159 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.221 ±(99.9%) 2.849 ms/op [Average]
  (min, avg, max) = (3.106, 3.221, 3.399), stdev = 0.156
  CI (99.9%): [0.372, 6.070] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.236 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (3.040, 3.082, 3.150), stdev = 0.059
  CI (99.9%): [2.005, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 7.916 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.005 ms/op
Iteration   1: 3.132 ±(99.9%) 0.005 ms/op
Iteration   2: 3.190 ±(99.9%) 0.004 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.176 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.132, 3.176, 3.206), stdev = 0.039
  CI (99.9%): [2.462, 3.890] (assumes normal distribution)


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
# Warmup Iteration   1: 8.707 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.005 ms/op
Iteration   1: 3.727 ±(99.9%) 0.008 ms/op
Iteration   2: 3.756 ±(99.9%) 0.007 ms/op
Iteration   3: 3.728 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.727, 3.737, 3.756), stdev = 0.016
  CI (99.9%): [3.441, 4.033] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.343 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  17.250 ms/op
                 createUser·p0.9999: 22.877 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  11.923 ms/op
                 createUser·p0.9999: 24.889 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294316
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22836 
    [ 2.500,  5.000) = 264966 
    [ 5.000,  7.500) = 5700 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     24.857 ms/op
     p(99.9990) =     25.528 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  13.516 ms/op
                 existUser·p0.9999: 20.174 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  12.640 ms/op
                 existUser·p0.9999: 22.543 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303992
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24473 
    [ 2.500,  5.000) = 273334 
    [ 5.000,  7.500) = 4830 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 8.079 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
Iteration   1: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 19.344 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 31.850 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  9.819 ms/op
                 getUser·p0.9999: 22.814 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294243
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18027 
    [ 2.500,  5.000) = 270443 
    [ 5.000,  7.500) = 4966 
    [ 7.500, 10.000) = 421 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 8.239 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
Iteration   1: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.114 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.521 ms/op
                 listUser·p0.9999: 18.810 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.676 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.785 ms/op
                 listUser·p0.999:  14.222 ms/op
                 listUser·p0.9999: 16.094 ms/op
                 listUser·p1.00:   16.597 ms/op

Iteration   3: 3.736 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.694 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257350
  mean =      3.728 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 251487 
    [ 5.000,  7.500) = 4133 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     19.871 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.927 ± 3.466  ops/ms
ClientPb.existUser                       thrpt       3  10.322 ± 6.299  ops/ms
ClientPb.getUser                         thrpt       3  10.031 ± 6.574  ops/ms
ClientPb.listUser                        thrpt       3   8.559 ± 1.518  ops/ms
ClientPb.createUser                       avgt       3   3.221 ± 2.849   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 1.077   ms/op
ClientPb.getUser                          avgt       3   3.176 ± 0.714   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.296   ms/op
ClientPb.createUser                     sample  294316   3.259 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.941           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.857           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.854           ms/op
ClientPb.existUser                      sample  303992   3.153 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.360           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.404           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.379           ms/op
ClientPb.getUser                        sample  294243   3.260 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.777           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  257350   3.728 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.842           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.120           ms/op
