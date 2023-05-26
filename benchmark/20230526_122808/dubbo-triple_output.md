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
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 6.750 ops/ms
# Warmup Iteration   3: 9.203 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (9.670, 9.797, 9.887), stdev = 0.113
  CI (99.9%): [7.739, 11.854] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ops/ms
# Warmup Iteration   2: 9.771 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.568 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (10.447, 10.568, 10.635), stdev = 0.105
  CI (99.9%): [8.657, 12.479] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.511 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 9.315 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 9.856 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.004 ±(99.9%) 3.885 ops/ms [Average]
  (min, avg, max) = (9.856, 10.004, 10.248), stdev = 0.213
  CI (99.9%): [6.120, 13.889] (assumes normal distribution)


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
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 7.332 ops/ms
# Warmup Iteration   3: 8.381 ops/ms
Iteration   1: 8.426 ops/ms
Iteration   2: 8.554 ops/ms
Iteration   3: 8.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.517 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (8.426, 8.517, 8.572), stdev = 0.079
  CI (99.9%): [7.070, 9.965] (assumes normal distribution)


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
# Warmup Iteration   1: 8.500 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.005 ms/op
Iteration   1: 3.173 ±(99.9%) 0.002 ms/op
Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
Iteration   3: 3.131 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (3.131, 3.195, 3.281), stdev = 0.077
  CI (99.9%): [1.781, 4.609] (assumes normal distribution)


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
# Warmup Iteration   1: 6.670 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.004 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
Iteration   3: 3.104 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.006, 3.044, 3.104), stdev = 0.053
  CI (99.9%): [2.086, 4.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.943 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.009 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.232 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.190 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.116, 3.190, 3.232), stdev = 0.064
  CI (99.9%): [2.025, 4.354] (assumes normal distribution)


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
# Warmup Iteration   1: 9.119 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.007 ms/op
Iteration   1: 3.800 ±(99.9%) 0.008 ms/op
Iteration   2: 3.686 ±(99.9%) 0.012 ms/op
Iteration   3: 3.826 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.686, 3.771, 3.826), stdev = 0.074
  CI (99.9%): [2.415, 5.127] (assumes normal distribution)


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
# Warmup Iteration   1: 8.384 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  12.740 ms/op
                 createUser·p0.9999: 20.813 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  14.984 ms/op
                 createUser·p0.9999: 22.223 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  15.538 ms/op
                 createUser·p0.9999: 21.176 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294061
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21847 
    [ 2.500,  5.000) = 266271 
    [ 5.000,  7.500) = 5029 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.498 ms/op
     p(99.9900) =     21.155 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.307 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  12.075 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  14.763 ms/op
                 existUser·p0.9999: 23.531 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.183 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  15.024 ms/op
                 existUser·p0.9999: 22.969 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305137
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10467 
    [ 2.500,  5.000) = 289852 
    [ 5.000,  7.500) = 3847 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.973 ms/op
     p(99.9900) =     23.019 ms/op
     p(99.9990) =     23.952 ms/op
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
# Warmup Iteration   1: 7.978 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  17.360 ms/op
                 getUser·p0.9999: 21.894 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  13.550 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  14.352 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296706
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14785 
    [ 2.500,  5.000) = 275400 
    [ 5.000,  7.500) = 5282 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     14.619 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.581 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 8.740 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
Iteration   1: 3.748 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.648 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.132 ms/op
                 listUser·p0.9999: 16.727 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.798 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.246 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255216
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 248436 
    [ 5.000,  7.500) = 4788 
    [ 7.500, 10.000) = 1219 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     19.557 ms/op
     p(99.9990) =     22.293 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 2.057  ops/ms
ClientPb.existUser                       thrpt       3  10.568 ± 1.911  ops/ms
ClientPb.getUser                         thrpt       3  10.004 ± 3.885  ops/ms
ClientPb.listUser                        thrpt       3   8.517 ± 1.447  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 1.414   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 0.958   ms/op
ClientPb.getUser                          avgt       3   3.190 ± 1.165   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 1.356   ms/op
ClientPb.createUser                     sample  294061   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.155           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.577           ms/op
ClientPb.existUser                      sample  305137   3.144 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.016           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.973           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.019           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.379           ms/op
ClientPb.getUser                        sample  296706   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.619           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.725           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.938           ms/op
ClientPb.listUser                       sample  255216   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
