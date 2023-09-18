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
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 5.874 ops/ms
# Warmup Iteration   3: 8.785 ops/ms
Iteration   1: 9.676 ops/ms
Iteration   2: 9.547 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.684 ±(99.9%) 2.593 ops/ms [Average]
  (min, avg, max) = (9.547, 9.684, 9.831), stdev = 0.142
  CI (99.9%): [7.092, 12.277] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 9.911 ops/ms
Iteration   1: 9.796 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 9.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.866 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (9.796, 9.866, 9.937), stdev = 0.070
  CI (99.9%): [8.582, 11.149] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 9.517 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.770 ops/ms
Iteration   3: 9.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.703 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (9.628, 9.703, 9.770), stdev = 0.071
  CI (99.9%): [8.406, 11.000] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 7.153 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 8.144 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.226 ±(99.9%) 1.300 ops/ms [Average]
  (min, avg, max) = (8.144, 8.226, 8.272), stdev = 0.071
  CI (99.9%): [6.926, 9.526] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.472 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.003 ms/op
Iteration   1: 3.335 ±(99.9%) 0.004 ms/op
Iteration   2: 3.198 ±(99.9%) 0.004 ms/op
Iteration   3: 3.274 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.198, 3.269, 3.335), stdev = 0.068
  CI (99.9%): [2.021, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.490 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.002 ms/op
Iteration   1: 3.236 ±(99.9%) 0.004 ms/op
Iteration   2: 3.176 ±(99.9%) 0.003 ms/op
Iteration   3: 3.199 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.176, 3.204, 3.236), stdev = 0.030
  CI (99.9%): [2.660, 3.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.293 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.002 ms/op
Iteration   1: 3.357 ±(99.9%) 0.003 ms/op
Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
Iteration   3: 3.293 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.295 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.235, 3.295, 3.357), stdev = 0.061
  CI (99.9%): [2.176, 4.414] (assumes normal distribution)


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
# Warmup Iteration   1: 9.285 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.005 ms/op
Iteration   1: 3.812 ±(99.9%) 0.006 ms/op
Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
Iteration   3: 3.778 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.803 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.778, 3.803, 3.819), stdev = 0.022
  CI (99.9%): [3.408, 4.199] (assumes normal distribution)


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
# Warmup Iteration   1: 8.972 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  12.175 ms/op
                 createUser·p0.9999: 20.360 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.339 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   3: 3.320 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  14.854 ms/op
                 createUser·p0.9999: 21.880 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288855
  mean =      3.322 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12926 
    [ 2.500,  5.000) = 271380 
    [ 5.000,  7.500) = 3523 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     15.214 ms/op
     p(99.9900) =     21.008 ms/op
     p(99.9990) =     22.505 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.239 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  13.878 ms/op
                 existUser·p0.9999: 20.209 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 23.298 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.286 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  16.174 ms/op
                 existUser·p0.9999: 45.078 ms/op
                 existUser·p1.00:   47.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295401
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 289166 
    [ 5.000, 10.000) = 5682 
    [10.000, 15.000) = 292 
    [15.000, 20.000) = 119 
    [20.000, 25.000) = 110 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     41.610 ms/op
     p(99.9990) =     47.058 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


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
# Warmup Iteration   1: 8.652 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.419 ms/op
                 getUser·p0.999:  18.898 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  16.940 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  9.309 ms/op
                 getUser·p0.9999: 21.884 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287576
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10135 
    [ 2.500,  5.000) = 270622 
    [ 5.000,  7.500) = 5781 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.048 ms/op
     p(99.9000) =     16.768 ms/op
     p(99.9900) =     22.159 ms/op
     p(99.9990) =     23.638 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 8.864 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 19.247 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 16.702 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 15.930 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251024
  mean =      3.824 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 244740 
    [ 5.000,  7.500) = 4667 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     18.117 ms/op
     p(99.9990) =     20.118 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.684 ± 2.593  ops/ms
ClientPb.existUser                       thrpt       3   9.866 ± 1.283  ops/ms
ClientPb.getUser                         thrpt       3   9.703 ± 1.297  ops/ms
ClientPb.listUser                        thrpt       3   8.226 ± 1.300  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 1.248   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 0.544   ms/op
ClientPb.getUser                          avgt       3   3.295 ± 1.119   ms/op
ClientPb.listUser                         avgt       3   3.803 ± 0.395   ms/op
ClientPb.createUser                     sample  288855   3.322 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.926           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.214           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  295401   3.248 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.110           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.681           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.317           ms/op
ClientPb.getUser                        sample  287576   3.339 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.048           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.768           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.159           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.855           ms/op
ClientPb.listUser                       sample  251024   3.824 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.218           ms/op
