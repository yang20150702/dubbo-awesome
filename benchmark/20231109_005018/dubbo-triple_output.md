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
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 6.364 ops/ms
# Warmup Iteration   3: 9.342 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.545 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.672 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (9.545, 9.672, 9.787), stdev = 0.121
  CI (99.9%): [7.463, 11.881] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ops/ms
# Warmup Iteration   2: 9.377 ops/ms
# Warmup Iteration   3: 10.144 ops/ms
Iteration   1: 10.153 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.197 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (10.153, 10.197, 10.242), stdev = 0.045
  CI (99.9%): [9.377, 11.016] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ops/ms
# Warmup Iteration   2: 8.972 ops/ms
# Warmup Iteration   3: 9.688 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.711 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (9.515, 9.711, 9.871), stdev = 0.181
  CI (99.9%): [6.414, 13.009] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 7.813 ops/ms
# Warmup Iteration   3: 8.212 ops/ms
Iteration   1: 8.385 ops/ms
Iteration   2: 8.325 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.343 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (8.320, 8.343, 8.385), stdev = 0.036
  CI (99.9%): [7.683, 9.003] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.006 ms/op
Iteration   1: 3.307 ±(99.9%) 0.004 ms/op
Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
Iteration   3: 3.237 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.236, 3.260, 3.307), stdev = 0.041
  CI (99.9%): [2.517, 4.003] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.005 ms/op
Iteration   1: 3.156 ±(99.9%) 0.004 ms/op
Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
Iteration   3: 3.191 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.116, 3.154, 3.191), stdev = 0.038
  CI (99.9%): [2.465, 3.843] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.003 ms/op
Iteration   1: 3.343 ±(99.9%) 0.004 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.275 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.194, 3.271, 3.343), stdev = 0.075
  CI (99.9%): [1.911, 4.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.265 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.004 ms/op
Iteration   1: 3.858 ±(99.9%) 0.004 ms/op
Iteration   2: 3.794 ±(99.9%) 0.005 ms/op
Iteration   3: 3.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.834 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.794, 3.834, 3.858), stdev = 0.035
  CI (99.9%): [3.190, 4.479] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.565 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.387 ms/op
                 createUser·p0.999:  18.004 ms/op
                 createUser·p0.9999: 19.928 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  19.304 ms/op
                 createUser·p0.9999: 24.472 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.393 ms/op
                 createUser·p0.999:  11.482 ms/op
                 createUser·p0.9999: 19.532 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299213
  mean =      3.207 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13713 
    [ 2.500,  5.000) = 281667 
    [ 5.000,  7.500) = 3104 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.373 ms/op
     p(99.9000) =     16.266 ms/op
     p(99.9900) =     23.759 ms/op
     p(99.9990) =     24.971 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.307 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  11.833 ms/op
                 existUser·p0.9999: 20.550 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  14.321 ms/op
                 existUser·p0.9999: 20.967 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  15.024 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299017
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13782 
    [ 2.500,  5.000) = 278904 
    [ 5.000,  7.500) = 5477 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     14.925 ms/op
     p(99.9900) =     20.713 ms/op
     p(99.9990) =     21.531 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.548 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.011 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 18.949 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  8.313 ms/op
                 getUser·p0.9999: 20.614 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  16.343 ms/op
                 getUser·p0.9999: 20.224 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295221
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15337 
    [ 2.500,  5.000) = 274056 
    [ 5.000,  7.500) = 4987 
    [ 7.500, 10.000) = 249 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 212 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.007 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.569 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
Iteration   1: 3.787 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 20.370 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.870 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  14.496 ms/op
                 listUser·p0.9999: 17.864 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.718 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251404
  mean =      3.819 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 244049 
    [ 5.000,  7.500) = 6169 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 374 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     19.015 ms/op
     p(99.9990) =     20.774 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.672 ± 2.209  ops/ms
ClientPb.existUser                       thrpt       3  10.197 ± 0.819  ops/ms
ClientPb.getUser                         thrpt       3   9.711 ± 3.297  ops/ms
ClientPb.listUser                        thrpt       3   8.343 ± 0.660  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.743   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 0.689   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 1.360   ms/op
ClientPb.listUser                         avgt       3   3.834 ± 0.644   ms/op
ClientPb.createUser                     sample  299213   3.207 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.373           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.266           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.759           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  299017   3.211 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.925           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.889           ms/op
ClientPb.getUser                        sample  295221   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.777           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.201           ms/op
ClientPb.listUser                       sample  251404   3.819 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.317           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.015           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.906           ms/op
