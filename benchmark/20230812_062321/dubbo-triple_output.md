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
# Warmup Iteration   1: 2.577 ops/ms
# Warmup Iteration   2: 6.084 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.590 ops/ms
Iteration   3: 9.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.595 ±(99.9%) 4.208 ops/ms [Average]
  (min, avg, max) = (9.366, 9.595, 9.828), stdev = 0.231
  CI (99.9%): [5.387, 13.802] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 8.808 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.208 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.115 ±(99.9%) 9.665 ops/ms [Average]
  (min, avg, max) = (9.545, 10.115, 10.593), stdev = 0.530
  CI (99.9%): [0.450, 19.780] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 9.333 ops/ms
# Warmup Iteration   3: 9.626 ops/ms
Iteration   1: 10.261 ops/ms
Iteration   2: 9.844 ops/ms
Iteration   3: 9.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.867 ±(99.9%) 6.996 ops/ms [Average]
  (min, avg, max) = (9.495, 9.867, 10.261), stdev = 0.383
  CI (99.9%): [2.871, 16.863] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.430 ops/ms
Iteration   3: 8.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.465 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (8.338, 8.465, 8.627), stdev = 0.147
  CI (99.9%): [5.777, 11.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.512 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.007 ms/op
Iteration   1: 3.287 ±(99.9%) 0.008 ms/op
Iteration   2: 3.289 ±(99.9%) 0.005 ms/op
Iteration   3: 3.295 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.290 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (3.287, 3.290, 3.295), stdev = 0.004
  CI (99.9%): [3.220, 3.360] (assumes normal distribution)


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
# Warmup Iteration   1: 7.464 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.112 ±(99.9%) 0.004 ms/op
Iteration   3: 3.210 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (3.047, 3.123, 3.210), stdev = 0.082
  CI (99.9%): [1.630, 4.616] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.115 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.005 ms/op
Iteration   1: 3.319 ±(99.9%) 0.005 ms/op
Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
Iteration   3: 3.240 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.175, 3.245, 3.319), stdev = 0.072
  CI (99.9%): [1.928, 4.561] (assumes normal distribution)


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
# Warmup Iteration   1: 9.505 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.006 ms/op
Iteration   1: 3.818 ±(99.9%) 0.009 ms/op
Iteration   2: 3.820 ±(99.9%) 0.006 ms/op
Iteration   3: 3.759 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.799 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.759, 3.799, 3.820), stdev = 0.035
  CI (99.9%): [3.165, 4.433] (assumes normal distribution)


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
# Warmup Iteration   1: 7.931 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  17.115 ms/op
                 createUser·p0.9999: 21.874 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.684 ms/op
                 createUser·p0.9999: 25.474 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.247 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  17.304 ms/op
                 createUser·p0.9999: 22.923 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289188
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27564 
    [ 2.500,  5.000) = 254391 
    [ 5.000,  7.500) = 6095 
    [ 7.500, 10.000) = 778 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     17.295 ms/op
     p(99.9900) =     24.480 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 7.728 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
Iteration   1: 3.112 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 25.025 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  11.425 ms/op
                 existUser·p0.9999: 28.274 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 20.844 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305879
  mean =      3.139 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20679 
    [ 2.500,  5.000) = 278062 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     12.765 ms/op
     p(99.9900) =     26.818 ms/op
     p(99.9990) =     28.568 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 8.604 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
Iteration   1: 3.233 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  15.175 ms/op
                 getUser·p0.9999: 18.393 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  15.013 ms/op
                 getUser·p0.9999: 18.006 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 3.339 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  16.810 ms/op
                 getUser·p0.9999: 21.968 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293046
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13572 
    [ 2.500,  5.000) = 268554 
    [ 5.000,  7.500) = 9335 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     15.580 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     22.383 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 8.806 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.012 ms/op
Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.276 ms/op
                 listUser·p0.999:  16.383 ms/op
                 listUser·p0.9999: 22.106 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 15.401 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251948
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 241665 
    [ 5.000,  7.500) = 7548 
    [ 7.500, 10.000) = 1760 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     20.598 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.595 ± 4.208  ops/ms
ClientPb.existUser                       thrpt       3  10.115 ± 9.665  ops/ms
ClientPb.getUser                         thrpt       3   9.867 ± 6.996  ops/ms
ClientPb.listUser                        thrpt       3   8.465 ± 2.688  ops/ms
ClientPb.createUser                       avgt       3   3.290 ± 0.070   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 1.493   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 1.316   ms/op
ClientPb.listUser                         avgt       3   3.799 ± 0.634   ms/op
ClientPb.createUser                     sample  289188   3.318 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.247           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.295           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.480           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  305879   3.139 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.713           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.738           ms/op
ClientPb.getUser                        sample  293046   3.274 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.711           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.580           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.643           ms/op
ClientPb.listUser                       sample  251948   3.806 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.489           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.598           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.839           ms/op
