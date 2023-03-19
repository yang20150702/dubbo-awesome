# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 5.920 ops/ms
# Warmup Iteration   3: 8.507 ops/ms
Iteration   1: 8.975 ops/ms
Iteration   2: 9.191 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.229 ±(99.9%) 5.032 ops/ms [Average]
  (min, avg, max) = (8.975, 9.229, 9.522), stdev = 0.276
  CI (99.9%): [4.197, 14.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.652 ops/ms
# Warmup Iteration   3: 9.644 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.795 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.763 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (9.646, 9.763, 9.850), stdev = 0.105
  CI (99.9%): [7.840, 11.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 8.575 ops/ms
# Warmup Iteration   3: 9.299 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.805 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.479 ±(99.9%) 5.609 ops/ms [Average]
  (min, avg, max) = (9.194, 9.479, 9.805), stdev = 0.307
  CI (99.9%): [3.870, 15.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.448 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 7.898 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.970 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (7.863, 7.970, 8.149), stdev = 0.156
  CI (99.9%): [5.125, 10.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.132 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.010 ms/op
Iteration   1: 3.363 ±(99.9%) 0.011 ms/op
Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
Iteration   3: 3.359 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.355 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.343, 3.355, 3.363), stdev = 0.011
  CI (99.9%): [3.159, 3.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.822 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.005 ms/op
Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
Iteration   3: 3.304 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.217, 3.256, 3.304), stdev = 0.045
  CI (99.9%): [2.442, 4.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.070 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.008 ms/op
Iteration   1: 3.585 ±(99.9%) 0.004 ms/op
Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
Iteration   3: 3.398 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 2.123 ms/op [Average]
  (min, avg, max) = (3.371, 3.451, 3.585), stdev = 0.116
  CI (99.9%): [1.328, 5.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.328 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
Iteration   3: 3.996 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.986 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.979, 3.986, 3.996), stdev = 0.009
  CI (99.9%): [3.830, 4.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.778 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.012 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 23.226 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  22.175 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 26.897 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274959
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2675 
    [ 2.500,  5.000) = 266057 
    [ 5.000,  7.500) = 5122 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     26.412 ms/op
     p(99.9990) =     27.501 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.438 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.861 ms/op
                 existUser·p0.9999: 22.911 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  13.024 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   6.166 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 25.833 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294380
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8774 
    [ 2.500,  5.000) = 281229 
    [ 5.000,  7.500) = 3515 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     12.521 ms/op
     p(99.9900) =     24.959 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.930 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.011 ms/op
Iteration   1: 3.614 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  10.365 ms/op
                 getUser·p0.9999: 20.288 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.579 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  19.550 ms/op
                 getUser·p0.9999: 22.153 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.554 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  22.551 ms/op
                 getUser·p0.9999: 29.983 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267774
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4436 
    [ 2.500,  5.000) = 252044 
    [ 5.000,  7.500) = 9584 
    [ 7.500, 10.000) = 1267 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.584 ms/op
     p(99.9900) =     27.802 ms/op
     p(99.9990) =     30.244 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.968 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
Iteration   1: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  22.157 ms/op
                 listUser·p0.9999: 30.784 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 4.113 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 26.615 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239860
  mean =      4.002 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 232542 
    [ 5.000,  7.500) = 5058 
    [ 7.500, 10.000) = 1264 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     29.202 ms/op
     p(99.9990) =     31.615 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.229 ± 5.032  ops/ms
ClientPb.existUser                       thrpt       3   9.763 ± 1.924  ops/ms
ClientPb.getUser                         thrpt       3   9.479 ± 5.609  ops/ms
ClientPb.listUser                        thrpt       3   7.970 ± 2.845  ops/ms
ClientPb.createUser                       avgt       3   3.355 ± 0.196   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 0.814   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 2.123   ms/op
ClientPb.listUser                         avgt       3   3.986 ± 0.157   ms/op
ClientPb.createUser                     sample  274959   3.489 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.227           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.447           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  294380   3.260 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.959           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.182           ms/op
ClientPb.getUser                        sample  267774   3.582 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.524           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.584           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.802           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  239860   4.002 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.972           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.202           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
