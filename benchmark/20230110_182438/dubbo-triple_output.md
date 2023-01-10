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
# Warmup Iteration   1: 1.130 ops/ms
# Warmup Iteration   2: 2.899 ops/ms
# Warmup Iteration   3: 5.657 ops/ms
Iteration   1: 5.689 ops/ms
Iteration   2: 5.800 ops/ms
Iteration   3: 5.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.792 ±(99.9%) 1.802 ops/ms [Average]
  (min, avg, max) = (5.689, 5.792, 5.886), stdev = 0.099
  CI (99.9%): [3.990, 7.594] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 5.032 ops/ms
# Warmup Iteration   3: 6.036 ops/ms
Iteration   1: 6.184 ops/ms
Iteration   2: 6.342 ops/ms
Iteration   3: 6.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.207 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (6.096, 6.207, 6.342), stdev = 0.124
  CI (99.9%): [3.939, 8.475] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.835 ops/ms
# Warmup Iteration   3: 5.676 ops/ms
Iteration   1: 6.031 ops/ms
Iteration   2: 6.065 ops/ms
Iteration   3: 6.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.040 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (6.023, 6.040, 6.065), stdev = 0.022
  CI (99.9%): [5.637, 6.442] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.557 ops/ms
# Warmup Iteration   2: 3.835 ops/ms
# Warmup Iteration   3: 5.059 ops/ms
Iteration   1: 5.170 ops/ms
Iteration   2: 4.785 ops/ms
Iteration   3: 4.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.979 ±(99.9%) 3.511 ops/ms [Average]
  (min, avg, max) = (4.785, 4.979, 5.170), stdev = 0.192
  CI (99.9%): [1.468, 8.491] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.216 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.759 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.422 ±(99.9%) 0.022 ms/op
Iteration   1: 5.696 ±(99.9%) 0.012 ms/op
Iteration   2: 5.678 ±(99.9%) 0.014 ms/op
Iteration   3: 5.454 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.610 ±(99.9%) 2.456 ms/op [Average]
  (min, avg, max) = (5.454, 5.610, 5.696), stdev = 0.135
  CI (99.9%): [3.153, 8.066] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.123 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.349 ±(99.9%) 0.015 ms/op
Iteration   1: 5.222 ±(99.9%) 0.012 ms/op
Iteration   2: 5.200 ±(99.9%) 0.011 ms/op
Iteration   3: 5.323 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.248 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (5.200, 5.248, 5.323), stdev = 0.065
  CI (99.9%): [4.057, 6.440] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.712 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.490 ±(99.9%) 0.009 ms/op
Iteration   1: 5.674 ±(99.9%) 0.010 ms/op
Iteration   2: 5.770 ±(99.9%) 0.012 ms/op
Iteration   3: 5.429 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.624 ±(99.9%) 3.201 ms/op [Average]
  (min, avg, max) = (5.429, 5.624, 5.770), stdev = 0.175
  CI (99.9%): [2.423, 8.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.591 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.352 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.263 ±(99.9%) 0.018 ms/op
Iteration   1: 6.396 ±(99.9%) 0.016 ms/op
Iteration   2: 6.389 ±(99.9%) 0.013 ms/op
Iteration   3: 6.367 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.384 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (6.367, 6.384, 6.396), stdev = 0.015
  CI (99.9%): [6.109, 6.660] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.899 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.741 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.689 ±(99.9%) 0.024 ms/op
Iteration   1: 5.419 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  24.311 ms/op
                 createUser·p0.9999: 31.883 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 5.549 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  24.684 ms/op
                 createUser·p0.9999: 28.520 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 5.380 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  23.873 ms/op
                 createUser·p0.9999: 29.106 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176285
  mean =      5.448 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 74498 
    [ 5.000,  7.500) = 92236 
    [ 7.500, 10.000) = 7354 
    [10.000, 12.500) = 1300 
    [12.500, 15.000) = 426 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     24.304 ms/op
     p(99.9900) =     29.286 ms/op
     p(99.9990) =     31.957 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.166 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.087 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.342 ±(99.9%) 0.021 ms/op
Iteration   1: 4.983 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.201 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  23.190 ms/op
                 existUser·p0.9999: 30.818 ms/op
                 existUser·p1.00:   32.932 ms/op

Iteration   2: 5.145 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   7.272 ms/op
                 existUser·p0.99:   10.200 ms/op
                 existUser·p0.999:  22.245 ms/op
                 existUser·p0.9999: 27.904 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   3: 5.115 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.952 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.234 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  23.792 ms/op
                 existUser·p0.9999: 27.550 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188773
  mean =      5.080 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 115913 
    [ 5.000,  7.500) = 65237 
    [ 7.500, 10.000) = 6048 
    [10.000, 12.500) = 949 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.551 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.874 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 17.020 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.281 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.021 ms/op
Iteration   1: 5.432 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   10.719 ms/op
                 getUser·p0.999:  27.562 ms/op
                 getUser·p0.9999: 33.394 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   2: 5.387 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.921 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   7.469 ms/op
                 getUser·p0.99:   9.990 ms/op
                 getUser·p0.999:  22.891 ms/op
                 getUser·p0.9999: 25.661 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 5.090 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.459 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.726 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  23.908 ms/op
                 getUser·p0.9999: 31.513 ms/op
                 getUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181165
  mean =      5.298 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 84004 
    [ 5.000,  7.500) = 89170 
    [ 7.500, 10.000) = 6164 
    [10.000, 12.500) = 1234 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     23.418 ms/op
     p(99.9900) =     32.007 ms/op
     p(99.9990) =     33.788 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 19.225 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 7.302 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.385 ±(99.9%) 0.028 ms/op
Iteration   1: 6.721 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  25.672 ms/op
                 listUser·p0.9999: 27.959 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   2: 6.104 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  27.937 ms/op
                 listUser·p0.9999: 31.680 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   3: 6.109 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.614 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  23.699 ms/op
                 listUser·p0.9999: 27.542 ms/op
                 listUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152365
  mean =      6.298 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 11659 
    [ 5.000,  7.500) = 121995 
    [ 7.500, 10.000) = 14109 
    [10.000, 12.500) = 3478 
    [12.500, 15.000) = 494 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 131 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.054 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.832 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.792 ± 1.802  ops/ms
ClientPb.existUser                       thrpt       3   6.207 ± 2.268  ops/ms
ClientPb.getUser                         thrpt       3   6.040 ± 0.402  ops/ms
ClientPb.listUser                        thrpt       3   4.979 ± 3.511  ops/ms
ClientPb.createUser                       avgt       3   5.610 ± 2.456   ms/op
ClientPb.existUser                        avgt       3   5.248 ± 1.191   ms/op
ClientPb.getUser                          avgt       3   5.624 ± 3.201   ms/op
ClientPb.listUser                         avgt       3   6.384 ± 0.275   ms/op
ClientPb.createUser                     sample  176285   5.448 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.453           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.304           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.286           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  188773   5.080 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.767           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.634           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.212           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  181165   5.298 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.459           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.242           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.994           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.418           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  152365   6.298 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.054           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.846           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.116           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.015           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539           ms/op
