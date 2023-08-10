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
# Warmup Iteration   1: 2.600 ops/ms
# Warmup Iteration   2: 6.351 ops/ms
# Warmup Iteration   3: 9.172 ops/ms
Iteration   1: 9.859 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.806 ±(99.9%) 3.426 ops/ms [Average]
  (min, avg, max) = (9.598, 9.806, 9.962), stdev = 0.188
  CI (99.9%): [6.380, 13.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.836 ops/ms
# Warmup Iteration   2: 9.250 ops/ms
# Warmup Iteration   3: 9.885 ops/ms
Iteration   1: 10.026 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.034 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (9.851, 10.034, 10.227), stdev = 0.188
  CI (99.9%): [6.599, 13.470] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.238 ops/ms
# Warmup Iteration   2: 8.307 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.878 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (9.775, 9.878, 9.981), stdev = 0.103
  CI (99.9%): [8.000, 11.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 8.200 ops/ms
Iteration   1: 8.587 ops/ms
Iteration   2: 8.215 ops/ms
Iteration   3: 8.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.476 ±(99.9%) 4.141 ops/ms [Average]
  (min, avg, max) = (8.215, 8.476, 8.627), stdev = 0.227
  CI (99.9%): [4.335, 12.617] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.796 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.004 ms/op
Iteration   1: 3.396 ±(99.9%) 0.005 ms/op
Iteration   2: 3.261 ±(99.9%) 0.006 ms/op
Iteration   3: 3.194 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 1.872 ms/op [Average]
  (min, avg, max) = (3.194, 3.284, 3.396), stdev = 0.103
  CI (99.9%): [1.412, 5.155] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
Iteration   3: 3.108 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.104 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.073, 3.104, 3.130), stdev = 0.029
  CI (99.9%): [2.583, 3.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.232 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.002 ms/op
Iteration   1: 3.141 ±(99.9%) 0.005 ms/op
Iteration   2: 3.303 ±(99.9%) 0.006 ms/op
Iteration   3: 3.312 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.252 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (3.141, 3.252, 3.312), stdev = 0.096
  CI (99.9%): [1.492, 5.012] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.597 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.007 ms/op
Iteration   1: 3.896 ±(99.9%) 0.007 ms/op
Iteration   2: 3.850 ±(99.9%) 0.008 ms/op
Iteration   3: 3.800 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.849 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.800, 3.849, 3.896), stdev = 0.048
  CI (99.9%): [2.969, 4.728] (assumes normal distribution)


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
# Warmup Iteration   1: 9.142 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
Iteration   1: 3.220 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   6.057 ms/op
                 createUser·p0.999:  13.036 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 3.282 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.839 ms/op
                 createUser·p0.999:  19.938 ms/op
                 createUser·p0.9999: 26.059 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293465
  mean =      3.270 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27211 
    [ 2.500,  5.000) = 258741 
    [ 5.000,  7.500) = 6158 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     24.663 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.461 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.411 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.785 ms/op
                 existUser·p0.9999: 20.189 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.526 ms/op
                 existUser·p0.999:  8.928 ms/op
                 existUser·p0.9999: 27.352 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  11.381 ms/op
                 existUser·p0.9999: 23.171 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301127
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9583 
    [ 2.500,  5.000) = 282971 
    [ 5.000,  7.500) = 7138 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     25.682 ms/op
     p(99.9990) =     27.983 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.440 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
Iteration   1: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.696 ms/op
                 getUser·p0.999:  13.369 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 26.519 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  13.952 ms/op
                 getUser·p0.9999: 27.999 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290755
  mean =      3.299 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13967 
    [ 2.500,  5.000) = 267268 
    [ 5.000,  7.500) = 7946 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     27.097 ms/op
     p(99.9990) =     28.675 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 9.397 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.887 ms/op
                 listUser·p0.999:  14.957 ms/op
                 listUser·p0.9999: 19.617 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  14.028 ms/op
                 listUser·p0.9999: 20.096 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248548
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 237508 
    [ 5.000,  7.500) = 8298 
    [ 7.500, 10.000) = 1918 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.806 ± 3.426  ops/ms
ClientPb.existUser                       thrpt       3  10.034 ± 3.435  ops/ms
ClientPb.getUser                         thrpt       3   9.878 ± 1.878  ops/ms
ClientPb.listUser                        thrpt       3   8.476 ± 4.141  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 1.872   ms/op
ClientPb.existUser                        avgt       3   3.104 ± 0.520   ms/op
ClientPb.getUser                          avgt       3   3.252 ± 1.760   ms/op
ClientPb.listUser                         avgt       3   3.849 ± 0.880   ms/op
ClientPb.createUser                     sample  293465   3.270 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.427           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.466           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.663           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  301127   3.187 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.411           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.682           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  290755   3.299 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.116           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.369           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.097           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  248548   3.863 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
