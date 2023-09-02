# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.556 ops/ms
# Warmup Iteration   2: 6.094 ops/ms
# Warmup Iteration   3: 9.358 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 9.613 ops/ms
Iteration   3: 9.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.807 ±(99.9%) 3.160 ops/ms [Average]
  (min, avg, max) = (9.613, 9.807, 9.946), stdev = 0.173
  CI (99.9%): [6.647, 12.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 8.587 ops/ms
# Warmup Iteration   3: 9.653 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 9.961 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.008 ±(99.9%) 3.391 ops/ms [Average]
  (min, avg, max) = (9.850, 10.008, 10.213), stdev = 0.186
  CI (99.9%): [6.617, 13.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 9.335 ops/ms
Iteration   1: 9.551 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.906 ±(99.9%) 6.571 ops/ms [Average]
  (min, avg, max) = (9.551, 9.906, 10.271), stdev = 0.360
  CI (99.9%): [3.335, 16.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.382 ops/ms
# Warmup Iteration   2: 7.771 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.432 ops/ms
Iteration   3: 8.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.456 ±(99.9%) 0.734 ops/ms [Average]
  (min, avg, max) = (8.432, 8.456, 8.502), stdev = 0.040
  CI (99.9%): [7.721, 9.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.003 ms/op
Iteration   1: 3.199 ±(99.9%) 0.005 ms/op
Iteration   2: 3.210 ±(99.9%) 0.005 ms/op
Iteration   3: 3.289 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.199, 3.233, 3.289), stdev = 0.049
  CI (99.9%): [2.331, 4.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.189 ±(99.9%) 0.004 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.118 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.045, 3.118, 3.189), stdev = 0.072
  CI (99.9%): [1.805, 4.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.133 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.003 ms/op
Iteration   1: 3.260 ±(99.9%) 0.004 ms/op
Iteration   2: 3.342 ±(99.9%) 0.005 ms/op
Iteration   3: 3.234 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.279 ±(99.9%) 1.034 ms/op [Average]
  (min, avg, max) = (3.234, 3.279, 3.342), stdev = 0.057
  CI (99.9%): [2.245, 4.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.201 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.009 ms/op
Iteration   1: 3.819 ±(99.9%) 0.007 ms/op
Iteration   2: 3.793 ±(99.9%) 0.004 ms/op
Iteration   3: 3.864 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.826 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.793, 3.826, 3.864), stdev = 0.036
  CI (99.9%): [3.172, 4.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.948 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
Iteration   1: 3.256 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  15.840 ms/op
                 createUser·p0.9999: 20.388 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  12.126 ms/op
                 createUser·p0.9999: 21.625 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.262 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297007
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25524 
    [ 2.500,  5.000) = 264950 
    [ 5.000,  7.500) = 4971 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     24.127 ms/op
     p(99.9990) =     25.593 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.198 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.782 ms/op
                 existUser·p0.999:  12.438 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  12.722 ms/op
                 existUser·p0.9999: 21.289 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 3.223 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  10.613 ms/op
                 existUser·p0.9999: 39.196 ms/op
                 existUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295612
  mean =      3.245 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21251 
    [ 2.500,  5.000) = 264874 
    [ 5.000,  7.500) = 7905 
    [ 7.500, 10.000) = 1036 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     12.638 ms/op
     p(99.9900) =     37.290 ms/op
     p(99.9990) =     39.396 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.116 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.012 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  11.178 ms/op
                 getUser·p0.9999: 19.864 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  19.380 ms/op
                 getUser·p0.9999: 21.692 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  9.988 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293202
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16148 
    [ 2.500,  5.000) = 268702 
    [ 5.000,  7.500) = 6837 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     24.119 ms/op
     p(99.9990) =     25.725 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.012 ms/op
Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  14.332 ms/op
                 listUser·p0.9999: 26.007 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 20.825 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250413
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 241795 
    [ 5.000,  7.500) = 6015 
    [ 7.500, 10.000) = 1718 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.625 ms/op
     p(99.9900) =     25.197 ms/op
     p(99.9990) =     26.296 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.807 ± 3.160  ops/ms
ClientPb.existUser                       thrpt       3  10.008 ± 3.391  ops/ms
ClientPb.getUser                         thrpt       3   9.906 ± 6.571  ops/ms
ClientPb.listUser                        thrpt       3   8.456 ± 0.734  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 0.901   ms/op
ClientPb.existUser                        avgt       3   3.118 ± 1.313   ms/op
ClientPb.getUser                          avgt       3   3.279 ± 1.034   ms/op
ClientPb.listUser                         avgt       3   3.826 ± 0.654   ms/op
ClientPb.createUser                     sample  297007   3.232 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.067           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.625           ms/op
ClientPb.existUser                      sample  295612   3.245 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.027           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.638           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.846           ms/op
ClientPb.getUser                        sample  293202   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.119           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.854           ms/op
ClientPb.listUser                       sample  250413   3.834 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.625           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.197           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
