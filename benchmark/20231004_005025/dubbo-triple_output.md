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
# Warmup Iteration   1: 2.530 ops/ms
# Warmup Iteration   2: 5.734 ops/ms
# Warmup Iteration   3: 9.116 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.893 ±(99.9%) 3.230 ops/ms [Average]
  (min, avg, max) = (9.705, 9.893, 10.057), stdev = 0.177
  CI (99.9%): [6.663, 13.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ops/ms
# Warmup Iteration   2: 8.875 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 10.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.172 ±(99.9%) 3.381 ops/ms [Average]
  (min, avg, max) = (9.981, 10.172, 10.351), stdev = 0.185
  CI (99.9%): [6.791, 13.553] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 9.283 ops/ms
# Warmup Iteration   3: 9.743 ops/ms
Iteration   1: 9.723 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.941 ±(99.9%) 3.684 ops/ms [Average]
  (min, avg, max) = (9.723, 9.941, 10.121), stdev = 0.202
  CI (99.9%): [6.258, 13.625] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.365 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (8.256, 8.365, 8.471), stdev = 0.107
  CI (99.9%): [6.404, 10.326] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.256 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.005 ms/op
Iteration   1: 3.153 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.140 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.105, 3.140, 3.161), stdev = 0.030
  CI (99.9%): [2.590, 3.689] (assumes normal distribution)


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
# Warmup Iteration   1: 7.832 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.004 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (3.098, 3.102, 3.108), stdev = 0.005
  CI (99.9%): [3.009, 3.196] (assumes normal distribution)


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
# Warmup Iteration   1: 9.532 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.004 ms/op
Iteration   1: 3.337 ±(99.9%) 0.004 ms/op
Iteration   2: 3.176 ±(99.9%) 0.002 ms/op
Iteration   3: 3.165 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.165, 3.226, 3.337), stdev = 0.096
  CI (99.9%): [1.471, 4.982] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.491 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.005 ms/op
Iteration   1: 3.784 ±(99.9%) 0.005 ms/op
Iteration   2: 3.756 ±(99.9%) 0.005 ms/op
Iteration   3: 3.727 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.727, 3.755, 3.784), stdev = 0.028
  CI (99.9%): [3.240, 4.271] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.285 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  12.569 ms/op
                 createUser·p0.9999: 19.665 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 23.802 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  13.657 ms/op
                 createUser·p0.9999: 17.369 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297590
  mean =      3.224 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21178 
    [ 2.500,  5.000) = 272272 
    [ 5.000,  7.500) = 3262 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     21.668 ms/op
     p(99.9990) =     24.905 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.992 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  15.464 ms/op
                 existUser·p0.9999: 19.658 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  13.006 ms/op
                 existUser·p0.9999: 21.848 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 21.572 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306165
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18937 
    [ 2.500,  5.000) = 282675 
    [ 5.000,  7.500) = 3607 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     11.300 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.280 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.585 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 18.273 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  16.330 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  14.123 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293940
  mean =      3.265 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10735 
    [ 2.500,  5.000) = 278134 
    [ 5.000,  7.500) = 4209 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     20.107 ms/op
     p(99.9990) =     21.207 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.023 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  17.542 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.749 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 13.861 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 15.756 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253682
  mean =      3.782 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 247112 
    [ 5.000,  7.500) = 5079 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 392 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     13.544 ms/op
     p(99.9900) =     19.207 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.893 ± 3.230  ops/ms
ClientPb.existUser                       thrpt       3  10.172 ± 3.381  ops/ms
ClientPb.getUser                         thrpt       3   9.941 ± 3.684  ops/ms
ClientPb.listUser                        thrpt       3   8.365 ± 1.961  ops/ms
ClientPb.createUser                       avgt       3   3.140 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.093   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 1.755   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 0.515   ms/op
ClientPb.createUser                     sample  297590   3.224 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.163           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.668           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.199           ms/op
ClientPb.existUser                      sample  306165   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.103           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.036           ms/op
ClientPb.getUser                        sample  293940   3.265 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.096           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.156           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.365           ms/op
ClientPb.listUser                       sample  253682   3.782 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.329           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.570           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.544           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
