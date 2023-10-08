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
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 4.829 ops/ms
# Warmup Iteration   3: 8.198 ops/ms
Iteration   1: 8.771 ops/ms
Iteration   2: 8.857 ops/ms
Iteration   3: 9.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.903 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (8.771, 8.903, 9.081), stdev = 0.160
  CI (99.9%): [5.991, 11.815] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.837 ops/ms
# Warmup Iteration   2: 8.613 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.494 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (9.291, 9.494, 9.611), stdev = 0.177
  CI (99.9%): [6.271, 12.716] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.938 ops/ms
# Warmup Iteration   2: 8.454 ops/ms
# Warmup Iteration   3: 8.891 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 8.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.083 ±(99.9%) 4.298 ops/ms [Average]
  (min, avg, max) = (8.811, 9.083, 9.225), stdev = 0.236
  CI (99.9%): [4.785, 13.381] (assumes normal distribution)


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
# Warmup Iteration   1: 2.702 ops/ms
# Warmup Iteration   2: 7.048 ops/ms
# Warmup Iteration   3: 7.475 ops/ms
Iteration   1: 7.338 ops/ms
Iteration   2: 7.515 ops/ms
Iteration   3: 7.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.462 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (7.338, 7.462, 7.534), stdev = 0.108
  CI (99.9%): [5.491, 9.433] (assumes normal distribution)


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
# Warmup Iteration   1: 9.230 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.006 ms/op
Iteration   1: 3.503 ±(99.9%) 0.009 ms/op
Iteration   2: 3.456 ±(99.9%) 0.005 ms/op
Iteration   3: 3.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.456, 3.479, 3.503), stdev = 0.024
  CI (99.9%): [3.047, 3.910] (assumes normal distribution)


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
# Warmup Iteration   1: 9.311 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.007 ms/op
Iteration   1: 3.401 ±(99.9%) 0.004 ms/op
Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
Iteration   3: 3.391 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.411 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (3.391, 3.411, 3.441), stdev = 0.027
  CI (99.9%): [2.925, 3.897] (assumes normal distribution)


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
# Warmup Iteration   1: 9.502 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.004 ms/op
Iteration   1: 3.644 ±(99.9%) 0.006 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 1.644 ms/op [Average]
  (min, avg, max) = (3.481, 3.540, 3.644), stdev = 0.090
  CI (99.9%): [1.896, 5.184] (assumes normal distribution)


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
# Warmup Iteration   1: 10.147 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.007 ms/op
Iteration   1: 4.133 ±(99.9%) 0.008 ms/op
Iteration   2: 4.288 ±(99.9%) 0.009 ms/op
Iteration   3: 4.211 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.211 ±(99.9%) 1.413 ms/op [Average]
  (min, avg, max) = (4.133, 4.211, 4.288), stdev = 0.077
  CI (99.9%): [2.798, 5.624] (assumes normal distribution)


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
# Warmup Iteration   1: 9.189 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.012 ms/op
Iteration   1: 3.632 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  21.130 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   2: 3.625 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  16.680 ms/op
                 createUser·p0.9999: 26.679 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 3.614 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  20.456 ms/op
                 createUser·p0.9999: 31.937 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264581
  mean =      3.624 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4091 
    [ 2.500,  5.000) = 252638 
    [ 5.000,  7.500) = 5948 
    [ 7.500, 10.000) = 1186 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     18.834 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     32.911 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 9.324 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
Iteration   1: 3.559 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  20.804 ms/op
                 existUser·p0.9999: 23.923 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.461 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  22.073 ms/op
                 existUser·p0.9999: 24.961 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275236
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3638 
    [ 2.500,  5.000) = 262727 
    [ 5.000,  7.500) = 6960 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     25.358 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 10.055 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
Iteration   1: 3.627 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  16.974 ms/op
                 getUser·p0.9999: 20.852 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  20.709 ms/op
                 getUser·p0.9999: 26.485 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266085
  mean =      3.604 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3796 
    [ 2.500,  5.000) = 251043 
    [ 5.000,  7.500) = 9246 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     18.017 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     27.144 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 11.493 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.015 ms/op
Iteration   1: 4.254 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 24.819 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.289 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 20.042 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.176 ms/op
                 listUser·p0.9999: 21.343 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226551
  mean =      4.238 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 213972 
    [ 5.000,  7.500) = 9102 
    [ 7.500, 10.000) = 2352 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     17.382 ms/op
     p(99.9900) =     24.205 ms/op
     p(99.9990) =     25.122 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.903 ± 2.912  ops/ms
ClientPb.existUser                       thrpt       3   9.494 ± 3.223  ops/ms
ClientPb.getUser                         thrpt       3   9.083 ± 4.298  ops/ms
ClientPb.listUser                        thrpt       3   7.462 ± 1.971  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   3.411 ± 0.486   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 1.644   ms/op
ClientPb.listUser                         avgt       3   4.211 ± 1.413   ms/op
ClientPb.createUser                     sample  264581   3.624 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.179           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  275236   3.485 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.358           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  266085   3.604 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.378           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.017           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.395           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  226551   4.238 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.331           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.382           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.205           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
